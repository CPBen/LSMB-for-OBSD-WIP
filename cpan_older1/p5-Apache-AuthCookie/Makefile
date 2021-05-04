# $OpenBSD$

COMMENT =	Perl Authentication and Authorization via cookies

DISTNAME =	Apache-AuthCookie-3.30

CATEGORIES =	cpan \
		apache-module

# Perl
PERMIT_PACKAGE =	Yes

MODULES =		cpan

CONFIGURE_ARGS+=	MP_APXS=${LOCALBASE}/sbin/apxs2 \
			MP_NO_THREADS=1

LIB_DEPENDS=            converters/libiconv \
                        devel/apr \
                        devel/apr-util

WANTLIB += apr-1 aprutil-1 c db expat iconv m perl pthread util

RUN_DEPENDS =		www/apache-httpd \
			devel/p5-Class-Load>=0.03 \
			devel/p5-Hash-MultiValue \
			www/p5-HTTP-Body \
			www/p5-URI>=1.36 \
			www/p5-WWW-Form-UrlEncoded
BUILD_DEPENDS =		${RUN_DEPENDS}
TEST_DEPENDS =		www/p5-URI>=1.31
USE_GMAKE=		Yes
PKG_ARCH =		*
PORTHOME=		${WRKDIR}
# Lines below not in the template
FIX_EXTRACT_PERMISSIONS =	Yes
.include <bsd.port.mk>
