# Created by: Giuseppe Pilichi aka Jacula Modyun <jacula@gmail.com>
# $FreeBSD$

PORTNAME=	statistics
PORTVERSION=	0.10.5.2
CATEGORIES=	math haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Library of statistical types, data, and functions

LICENSE=	BSD

USE_CABAL=	binary>=0.6.3.0 erf math-functions>=0.1.2 monad-par>=0.3.4 \
		mwc-random>=0.13.0.0 primitive>=0.3 vector>=0.7.1 \
		vector-algorithms>=0.4 vector-binary-instances>=0.2.1

INSTALL_PORTDATA=	${INSTALL_DATA} ${WRKSRC}/README.markdown ${STAGEDIR}${DATADIR}

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
