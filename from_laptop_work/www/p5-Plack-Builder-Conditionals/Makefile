# $OpenBSD: Makefile.template,v 1.85 2019/09/09 19:19:05 kmos Exp $

COMMENT =	Plack::Builder extension

DISTNAME =	Plack-Builder-Conditionals-0.05

CATEGORIES =	www

# Perl
PERMIT_PACKAGE =	Yes

MODULES =		cpan

BUILD_DEPENDS =		devel/p5-Module-Build>=0.38
RUN_DEPENDS =		devel/p5-List-MoreUtils \
			net/p5-Net-CIDR-Lite \
			www/p5-Plack>=0.9941

CONFIGURE_STYLE =	modbuild

PKG_ARCH =		*

.include <bsd.port.mk>
