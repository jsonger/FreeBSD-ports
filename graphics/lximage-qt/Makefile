# Created by: Olivier Duchateau
# $FreeBSD$

PORTNAME=	lximage-qt
PORTVERSION=	0.7.0
CATEGORIES=	graphics
MASTER_SITES=	LXQT

MAINTAINER=	jesper@schmitz.computer
COMMENT=	Image viewer and screenshot tool

LICENSE=	GPLv2

LIB_DEPENDS=	libexif.so:graphics/libexif \
	libmenu-cache.so:x11/menu-cache \
	libfm.so:x11/libfm

USES=	cmake:outsource compiler:c++11-lib desktop-file-utils gettext-runtime \
	localbase:ldflags lxqt pkgconfig qt:5 tar:xz
USE_GNOME=	glib20
USE_QT=		buildtools_build qmake_build core dbus gui linguisttools \
	network printsupport svg widgets x11extras
USE_LXQT=	buildtools libfmqt
USE_XORG=	ice sm x11 xcb xext xfixes
INSTALLS_ICONS=	yes

.include <bsd.port.mk>
