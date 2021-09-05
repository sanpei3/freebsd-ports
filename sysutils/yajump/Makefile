PORTNAME=	yajump
PORTVERSION=	0.40.0
CATEGORIES=	sysutils

MAINTAINER=	sanpei@freebsd.org
COMMENT=	helps you navigate faster by learning your habits.

LICENSE=	MIT

USES=	gmake go
USE_GITHUB=	yes
GH_ACCOUNT=	gsamokovarov
GH_PROJECT=	jump
GH_TAGNAME=	v${PORTVERSION}
GO_PKGNAME=       github.com/${GH_ACCOUNT}/${GH_PROJECT}

GO_TARGETS=	build

PLIST_FILES=    bin/jump \
                man/man1/jump.1.gz \
                man/man1/j.1.gz

do-build:
.for GO_TARGET in ${GO_TARGETS}
	@(cd ${GO_WRKSRC}; ${SETENV} ${MAKE_ENV} ${GO_ENV} ${GMAKE} ${GO_TARGET})
.endfor


do-install:
	${INSTALL_PROGRAM} ${WRKSRC}/jump ${STAGEDIR}${PREFIX}/bin
	${INSTALL_MAN} ${WRKSRC}/man/jump.1 ${STAGEDIR}${MAN1PREFIX}/man/man1/
	${INSTALL_MAN} ${WRKSRC}/man/j.1 ${STAGEDIR}${MAN1PREFIX}/man/man1/

.include <bsd.port.mk>
