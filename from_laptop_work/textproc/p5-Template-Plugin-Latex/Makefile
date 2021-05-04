# $OpenBSD: Makefile.template,v 1.85 2019/09/09 19:19:05 kmos Exp $

COMMENT =		LaTeX support for the Template Toolkit

DISTNAME=		Template-Plugin-Latex-3.12

CATEGORIES=		textproc

# Perl
PERMIT_PACKAGE=	Yes

MODULES=		cpan

RUN_DEPENDS=		textproc/p5-Template \
			textproc/p5-LaTeX-Driver \
			textproc/p5-LaTeX-Encode \
			textproc/p5-LaTeX-Table

PKG_ARCH =		*

.include <bsd.port.mk>
