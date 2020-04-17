############################################################ IDENT(1)
#
# $Title: Makefile for installing nfsiosnoop $
# $Copyright: 2020 Devin Teske. All rights reserved. $
# $FrauBSD: nfsiosnoop/GNUmakefile 2020-04-17 15:29:52 -0700 freebsdfrau $
#
############################################################ CONFIGURATION

DESTDIR=	
BINDIR=		$(DESTDIR)/usr/bin

############################################################ PATHS

CP_F=		cp -f
MKDIR_P=	mkdir -p
RM_F=		rm -f

############################################################ OBJECTS

PROG=		nfsiosnoop

############################################################ TARGETS

all:
	@printf "Options:\n"
	@printf "\tmake install\tInstall nfsiosnoop\n"
	@printf "\tmake uninstall\tUninstall nfsiosnoop\n"

install:
	$(MKDIR_P) $(BINDIR)
	$(CP_F) $(PROG) $(BINDIR)/

uninstall:
	$(RM_F) $(BINDIR)/$(PROG)

################################################################################
# END
################################################################################
