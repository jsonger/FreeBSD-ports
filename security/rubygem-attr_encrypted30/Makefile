# $FreeBSD$

PORTNAME=	attr_encrypted
PORTVERSION=	3.0.3
CATEGORIES=	security rubygems
MASTER_SITES=	RG
PKGNAMESUFFIX=	30

MAINTAINER=	mfechner@FreeBSD.org
COMMENT=	Generates attr_accessors that encrypt and decrypt attributes

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/MIT-LICENSE

DEPRECATED=	Obsoleted by update of www/gitlab. Please use security/rubygem-attr_encrypted instead.
EXPIRATION_DATE=	2018-06-30

RUN_DEPENDS=	rubygem-encryptor>=3.0.0:security/rubygem-encryptor

PORTSCOUT=	limit:^3\.0\.

NO_ARCH=	yes
USES=		gem
USE_RUBY=	yes

.include <bsd.port.mk>
