# $FreeBSD$

PORTNAME=	rmf
DISTVERSION=	g20180614
CATEGORIES=	science graphics
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	yuri@FreeBSD.org
COMMENT=	Library to support reading and writing of Rich Molecular Format files

LICENSE=	APACHE20
LICENSE_FILE=	${WRKSRC}/COPYING

BUILD_DEPENDS=	swig3.0:devel/swig30
LIB_DEPENDS=	libRMF.so:science/rmf

USES=		cmake:outsource python shebangfix
USE_GITHUB=	yes
GH_ACCOUNT=	salilab
GH_TAGNAME=	f917cf2
SHEBANG_GLOB=	*.py
USE_PYTHON=	flavors

CMAKE_ARGS=	-DCMAKE_INSTALL_PYTHONDIR:STRING=${PYTHON_SITELIBDIR}
BINARY_ALIAS=	python=${PYTHON_CMD}
LDFLAGS+=	-lRMF

.include <bsd.port.mk>
