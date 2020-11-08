# Created by: Yoshiro SANPEI Mihira<sanpei@FreeBSD.org>
# $FreeBSD$

PORTNAME=	codecov
PORTVERSION=	0.2.12
CATEGORIES=	rubygems
MASTER_SITES=	RG

MAINTAINER=	ruby@FreeBSD.org
COMMENT=	hosted code coverage

LICENSE=	MIT

BUILD_DEPENDS=	rubygem-minitest>=0:devel/rubygem-minitest \
		rubygem-minitest-ci>=0:devel/rubygem-minitest-ci \
		rubygem-mocha>=0:devel/rubygem-mocha \
		rubygem-rake>=13<14:devel/rubygem-rake \
		rubygem-rubocop>=0:devel/rubygem-rubocop \
		rubygem-webmock>=0:www/rubygem-webmock
RUN_DEPENDS=	rubygem-json>=0:devel/rubygem-json \
		rubygem-simplecov>=0:devel/rubygem-simplecov

NO_ARCH=	yes
USE_RUBY=	yes
USES=		gem

.include <bsd.port.mk>
