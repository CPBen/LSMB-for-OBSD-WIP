# $OpenBSD: Makefile.template,v 1.85 2019/09/09 19:19:05 kmos Exp $

COMMENT =	upload things to the CPAN

DISTNAME =	CPAN-Uploader-0.103013

CATEGORIES =	devel

# Perl
PERMIT_PACKAGE =	Yes

MODULES =		cpan

RUN_DEPENDS =		devel/p5-File-HomeDir \
			devel/p5-Getopt-Long-Descriptive>=0.084 \
			www/p5-HTTP-Message \
			www/p5-LWP-Protocol-https>=1 \
			www/p5-libwww

PKG_ARCH =		*

.include <bsd.port.mk>
