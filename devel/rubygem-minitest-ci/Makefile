# Created by: Yoshiro SANPEI Mihira<sanpei@FreeBSD.org>
# $FreeBSD$

PORTNAME=	minitest-ci
PORTVERSION=	3.4.0
CATEGORIES=	devel rubygems
MASTER_SITES=	RG

MAINTAINER=	ruby@FreeBSD.org
COMMENT=	Minitest Junit XML results that CircleCI can read.

BUILD_DEPENDS=	rubygem-bundler>=1.14:sysutils/rubygem-bundler \
		rubygem-json>=2:devel/rubygem-json \
		rubygem-nokogiri>=1.7.1:textproc/rubygem-nokogiri \
		rubygem-rake>=12:devel/rubygem-rake \
		rubygem-rspec>=0:devel/rubygem-rspec \
		rubygem-rdoc>=2.4.2:devel/rubygem-rdoc\
		rubygem-zentest>=0:devel/rubygem-zentest
RUN_DEPENDS=	rubygem-minitest>=5.0.6:devel/rubygem-minitest

LICENSE=	MIT

USES=		gem
USE_RUBY=	yes

NO_ARCH=	yes

.include <bsd.port.mk>
