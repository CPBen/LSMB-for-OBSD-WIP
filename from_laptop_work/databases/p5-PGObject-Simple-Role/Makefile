# $OpenBSD: Makefile.template,v 1.85 2019/09/09 19:19:05 kmos Exp $

COMMENT =	Moo/Moose mappers for minimalist PGObject framework

DISTNAME =	PGObject-Simple-Role-2.000002

CATEGORIES =	databases devel

# BSD
PERMIT_PACKAGE =	Yes

PKG_ARCH =		*

MODULES +=		cpan \
			databases/postgresql

RUN_DEPENDS =		databases/p5-PGObject-Simple>=3 \
			devel/p5-Moo

TEST_DEPENDS =		devel/p5-Test-Exception \
			devel/p5-Test-CheckManifest \
			databases/p5-DBI \
			databases/p5-DBD-Pg

MODPOSTGRESQL_TEST_CMD = \
			 ${LOCALBASE}/bin/psql -d postgres -c \
			 'CREATE ROLE postgres WITH LOGIN CREATEDB'; \
			 ${MAKE_PROGRAM} ${ALL_TEST_FLAGS} -f ${MAKE_FILE} ${TEST_TARGET}

MAKE_ENV +=		TEST_POD=1 \
			DB_TESTING=1 \
			RELEASE_TESTING=''


.include <bsd.port.mk>
