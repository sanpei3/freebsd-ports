# $FreeBSD$

PORTNAME=	coveralls
PORTVERSION=	0.8.23
CATEGORIES=	devel rubygems
MASTER_SITES=	RG

MAINTAINER=	ruby@FreeBSD.org
COMMENT=	A Ruby implementation of the Coveralls API

LICENSE=	MIT

BUILD_DEPENDS=	rubygem-bundler>=0:sysutils/rubygem-bundler
RUN_DEPENDS=	rubygem-json1>=1.8<3:devel/rubygem-json1 \
		rubygem-simplecov>0.16.1:devel/rubygem-simplecov \
		rubygem-term-ansicolor>1.3:devel/rubygem-term-ansicolor \
		rubygem-thor>=0.19.4<2:devel/rubygem-thor \
		rubygem-tins>1.6l:devel/rubygem-tins

USES=		gem
NO_ARCH=	yes
USE_RUBY=	yes

.include <bsd.port.mk>
