# $NetBSD: Makefile,v 1.33 2020/08/31 18:08:17 wiz Exp $

DISTNAME=	Log-Agent-1.003
PKGNAME=	p5-${DISTNAME}
PKGREVISION=	3
CATEGORIES=	devel perl5
MASTER_SITES=	${MASTER_SITE_PERL_CPAN:=Log/}
EXTRACT_USING=	gtar

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://metacpan.org/release/Log-Agent
COMMENT=	General logging framework aimed at reusable modules
LICENSE=	artistic-2.0

PERL5_PACKLIST=		auto/Log/Agent/.packlist

.include "../../lang/perl5/module.mk"
.include "../../mk/bsd.pkg.mk"
