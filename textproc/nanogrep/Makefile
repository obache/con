# $NetBSD: Makefile,v 1.1 2021/01/01 13:49:56 pin Exp $

DISTNAME=	nanogrep-1.2.1
CATEGORIES=	textproc
MASTER_SITES=	${MASTER_SITE_GITHUB:=Uniminin/}

MAINTAINER=	pin@NetBSD.org
HOMEPAGE=	https://github.com/Uniminin/nanogrep/
COMMENT=	Custom Implementation of minigrep with additional functionality
LICENSE=	mit

.include "cargo-depends.mk"

USE_LANGUAGES+=		c # rust, but needs a toolchain to link

INSTALLATION_DIRS=	bin

do-install:
	${INSTALL_PROGRAM} ${WRKSRC}/target/release/ng ${DESTDIR}${PREFIX}/bin

.include "../../lang/rust/cargo.mk"
.include "../../mk/bsd.pkg.mk"
