# Created by: Justin Edward Muniz <jmuniz@freebsd.org>
# $FreeBSD$

PORTNAME=	appy-remote-server
PORTVERSION=	0.1
CATEGORIES=	ports-mgmt
MASTER_SITES=	http://softlayer-dal.dl.sourceforge.net/project/appy/
DISTFILES=	appy-0.1.txz

MAINTAINER=	jmuniz@freebsd.org
COMMENT=	Stand-alone daemon for remote package management

LICENSE=	BSD

LIB_DEPENDS=	libpkg.so:${PORTSDIR}/ports-mgmt/pkg

ALL_TARGET=	buildServer
INSTALL_TARGET=	installServer

PLIST_FILES=	bin/appyd

.include <bsd.port.mk>