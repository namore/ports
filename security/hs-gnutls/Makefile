# $FreeBSD$

PORTNAME=	gnutls
PORTVERSION=	0.1.5
CATEGORIES=	security haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Bindings for GNU libgnutls

LICENSE=	GPLv3

USE_CABAL=	monads-tf>=0.1 transformers>=0.2

USES=		pkgconfig
LIB_DEPENDS=	gnutls.26:${PORTSDIR}/security/gnutls

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
