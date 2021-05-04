# $OpenBSD: Makefile.template,v 1.85 2019/09/09 19:19:05 kmos Exp $

COMMENT =	MVP config reader for .ini files

DISTNAME =	Config-MVP-Reader-INI-2.101463

CATEGORIES =	devel

# Perl
PERMIT_PACKAGE =	Yes

MODULES =		cpan

RUN_DEPENDS =		devel/p5-Config-MVP>=2 \
			devel/p5-Config-IniFiles \
			devel/p5-Moose

PKG_ARCH =		*

.include <bsd.port.mk>
