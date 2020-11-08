# Created by: Yoshiro SANPEI Mihira<sanpei@FreeBSD.org>
# $FreeBSD$

PORTNAME=	sendgrid-ruby
PORTVERSION=	6.3.7
CATEGORIES=	mail rubygems
MASTER_SITES=	RG

MAINTAINER=	ruby@FreeBSD.org
COMMENT=	Interact with Twilio SendGrids API in native Ruby

LICENSE=	MIT

BUILD_DEPENDS=	rubygem-faker>=0:devel/rubygem-faker \
		rubygem-minitest>=5.9<6:devel/rubygem-minitest \
		rubygem-pry>=0:devel/rubygem-pry \
		rubygem-rack>=0:www/rubygem-rack \
		rubygem-rake>=13<14:devel/rubygem-rake \
		rubygem-rspec>=0:devel/rubygem-rspec \
		rubygem-rubocop>=0:devel/rubygem-rubocop \
		rubygem-simplecov>=0.18.5:devel/rubygem-simplecov \
		rubygem-sinatra>=1.4.7<3:www/rubygem-sinatra
RUN_DEPENDS=	rubygem-ruby_http_client>=3.4<4:www/rubygem-ruby_http_client

NO_ARCH=	yes
USE_RUBY=	yes
USES=		gem

.include <bsd.port.mk>
