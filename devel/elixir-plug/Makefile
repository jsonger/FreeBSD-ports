# $FreeBSD$

PORTNAME=	plug
PORTVERSION=	1.4.5
DISTVERSIONPREFIX=	v
CATEGORIES=	devel
PKGNAMEPREFIX=	elixir-

MAINTAINER=	erlang@FreeBSD.org
COMMENT=	Composable modules for Elixir web applications

LICENSE=	APACHE20

USES=		elixir
USE_GITHUB=	yes
GH_ACCOUNT=	elixir-lang

MIX_BUILD_DEPS=	misc/elixir-mime
MIX_RUN_DEPS:=	${MIX_BUILD_DEPS}
MIX_REWRITE=	yes

.include <bsd.port.mk>
