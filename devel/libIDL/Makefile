# Created by: Maxim Sobolev <sobomax@FreeBSD.org>
# $FreeBSD$
#   $MCom: ports/devel/libIDL/Makefile,v 1.7 2010/04/02 17:27:42 kwm Exp $

PORTNAME=	libIDL
PORTVERSION=	0.8.14
PORTREVISION=	4
CATEGORIES=	devel
MASTER_SITES=	GNOME
DIST_SUBDIR=	gnome2

MAINTAINER=	desktop@FreeBSD.org
COMMENT=	Library for creating trees of CORBA IDL files

USES=		bison:alias gettext gmake gnome libtool:keepla localbase \
		pathfix pkgconfig tar:bzip2
USE_GNOME=	glib20
INSTALL_TARGET=	install-strip
USE_LDCONFIG=	yes
GNU_CONFIGURE=	yes
CONFIGURE_ARGS=	--with-html-dir=${PREFIX}/share/doc

INFO=		libIDL2

.include <bsd.port.mk>
