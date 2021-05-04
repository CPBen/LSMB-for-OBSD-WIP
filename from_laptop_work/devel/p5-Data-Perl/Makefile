# $OpenBSD: Makefile.template,v 1.85 2019/09/09 19:19:05 kmos Exp $

COMMENT =		collection of classes wrapping fundamental Perl data types

# This package is marked as alpha, but is no longer maintained.
# It is needed for another port

DISTNAME =		Data-Perl-0.002009

CATEGORIES =	devel

# Perl
PERMIT_PACKAGE =	Yes

MODULES =		cpan

PKG_ARCH =		*

RUN_DEPENDS =		devel/p5-Class-Method-Modifiers \
					devel/p5-List-MoreUtils \
					devel/p5-Role-Tiny \
					devel/p5-strictures \
					devel/p5-Module-Runtime

TEST_DEPENDS =		devel/p5-Test-Fatal \
					devel/p5-Test-Output

MAKE_ENV =		TEST_POD=Yes

.include <bsd.port.mk>
