# Makefile.in generated by automake 1.14 from Makefile.am.
# share/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2013 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.




am__is_gnu_make = test -n '$(MAKEFILE_LIST)' && test -n '$(MAKELEVEL)'
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/mednaffe
pkgincludedir = $(includedir)/mednaffe
pkglibdir = $(libdir)/mednaffe
pkglibexecdir = $(libexecdir)/mednaffe
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
subdir = share
DIST_COMMON = $(srcdir)/Makefile.in $(srcdir)/Makefile.am
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
SOURCES =
DIST_SOURCES =
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__installdirs = "$(DESTDIR)$(desktopdir)" "$(DESTDIR)$(icon128dir)" \
	"$(DESTDIR)$(icon16dir)" "$(DESTDIR)$(icon32dir)" \
	"$(DESTDIR)$(icon48dir)" "$(DESTDIR)$(icon64dir)" \
	"$(DESTDIR)$(iconsdir)" "$(DESTDIR)$(pixmapdir)"
DATA = $(desktop_DATA) $(icon128_DATA) $(icon16_DATA) $(icon32_DATA) \
	$(icon48_DATA) $(icon64_DATA) $(icons_DATA) $(pixmap_DATA)
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/aklein/mednaffe/missing aclocal-1.14
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AUTOCONF = ${SHELL} /home/aklein/mednaffe/missing autoconf
AUTOHEADER = ${SHELL} /home/aklein/mednaffe/missing autoheader
AUTOMAKE = ${SHELL} /home/aklein/mednaffe/missing automake-1.14
AWK = gawk
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -O2 -std=c99 -Wall -s -Wl,-export-dynamic
CPPFLAGS = 
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EXEEXT = 
GTK_CFLAGS = -pthread -I/usr/include/gtk-2.0 -I/usr/lib/gtk-2.0/include -I/usr/include/pango-1.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/libdrm -I/usr/include/libpng16 -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng16 -I/usr/include/pango-1.0 -I/usr/include/harfbuzz -I/usr/include/pango-1.0 -I/usr/include/freetype2 -I/usr/include/glib-2.0 -I/usr/lib/glib-2.0/include 
GTK_DEFINES = -DGTK2_ENABLED
GTK_LIBS = -lgtk-x11-2.0 -lgdk-x11-2.0 -lpangocairo-1.0 -latk-1.0 -lcairo -lgdk_pixbuf-2.0 -lgio-2.0 -lpangoft2-1.0 -lpango-1.0 -lgobject-2.0 -lfontconfig -lfreetype -lgthread-2.0 -pthread -lglib-2.0 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LDFLAGS = 
LIBOBJS = 
LIBS = 
LTLIBOBJS = 
MAKEINFO = ${SHELL} /home/aklein/mednaffe/missing makeinfo
MKDIR_P = /usr/bin/mkdir -p
OBJEXT = o
PACKAGE = mednaffe
PACKAGE_BUGREPORT = BUG-REPORT-ADDRESS
PACKAGE_NAME = mednaffe
PACKAGE_STRING = mednaffe 0.6
PACKAGE_TARNAME = mednaffe
PACKAGE_URL = 
PACKAGE_VERSION = 0.6
PATH_SEPARATOR = :
PKG_CONFIG = /usr/bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = 
SET_MAKE = 
SHELL = /bin/sh
STRIP = 
VERSION = 0.6
abs_builddir = /home/aklein/mednaffe/share
abs_srcdir = /home/aklein/mednaffe/share
abs_top_builddir = /home/aklein/mednaffe
abs_top_srcdir = /home/aklein/mednaffe
ac_ct_CC = gcc
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build_alias = 
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host_alias = 
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/aklein/mednaffe/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
EXTRA_DIST = \
  applications/mednaffe.desktop \
  pixmaps/mednaffe.png \
  icons/hicolor/16x16/apps/mednaffe.png \
  icons/hicolor/32x32/apps/mednaffe.png \
  icons/hicolor/48x48/apps/mednaffe.png \
  icons/hicolor/64x64/apps/mednaffe.png \
  icons/hicolor/128x128/apps/mednaffe.png \
  icons/hicolor/scalable/apps/mednaffe.svg 


# Desktop file
desktopdir = $(datadir)/applications
desktop_DATA = applications/mednaffe.desktop

# Pixmap file
pixmapdir = $(datadir)/pixmaps
pixmap_DATA = pixmaps/mednaffe.png

# Icon files
icon16dir = $(datadir)/icons/hicolor/16x16/apps
icon16_DATA = icons/hicolor/16x16/apps/mednaffe.png
icon32dir = $(datadir)/icons/hicolor/32x32/apps
icon32_DATA = icons/hicolor/32x32/apps/mednaffe.png
icon48dir = $(datadir)/icons/hicolor/48x48/apps
icon48_DATA = icons/hicolor/48x48/apps/mednaffe.png
icon64dir = $(datadir)/icons/hicolor/64x64/apps
icon64_DATA = icons/hicolor/64x64/apps/mednaffe.png
icon128dir = $(datadir)/icons/hicolor/128x128/apps
icon128_DATA = icons/hicolor/128x128/apps/mednaffe.png
iconsdir = $(datadir)/icons/hicolor/scalable/apps
icons_DATA = icons/hicolor/scalable/apps/mednaffe.svg
all: all-am

.SUFFIXES:
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign share/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign share/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
install-desktopDATA: $(desktop_DATA)
	@$(NORMAL_INSTALL)
	@list='$(desktop_DATA)'; test -n "$(desktopdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(desktopdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(desktopdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(desktopdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(desktopdir)" || exit $$?; \
	done

uninstall-desktopDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(desktop_DATA)'; test -n "$(desktopdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(desktopdir)'; $(am__uninstall_files_from_dir)
install-icon128DATA: $(icon128_DATA)
	@$(NORMAL_INSTALL)
	@list='$(icon128_DATA)'; test -n "$(icon128dir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(icon128dir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(icon128dir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(icon128dir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(icon128dir)" || exit $$?; \
	done

uninstall-icon128DATA:
	@$(NORMAL_UNINSTALL)
	@list='$(icon128_DATA)'; test -n "$(icon128dir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(icon128dir)'; $(am__uninstall_files_from_dir)
install-icon16DATA: $(icon16_DATA)
	@$(NORMAL_INSTALL)
	@list='$(icon16_DATA)'; test -n "$(icon16dir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(icon16dir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(icon16dir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(icon16dir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(icon16dir)" || exit $$?; \
	done

uninstall-icon16DATA:
	@$(NORMAL_UNINSTALL)
	@list='$(icon16_DATA)'; test -n "$(icon16dir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(icon16dir)'; $(am__uninstall_files_from_dir)
install-icon32DATA: $(icon32_DATA)
	@$(NORMAL_INSTALL)
	@list='$(icon32_DATA)'; test -n "$(icon32dir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(icon32dir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(icon32dir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(icon32dir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(icon32dir)" || exit $$?; \
	done

uninstall-icon32DATA:
	@$(NORMAL_UNINSTALL)
	@list='$(icon32_DATA)'; test -n "$(icon32dir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(icon32dir)'; $(am__uninstall_files_from_dir)
install-icon48DATA: $(icon48_DATA)
	@$(NORMAL_INSTALL)
	@list='$(icon48_DATA)'; test -n "$(icon48dir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(icon48dir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(icon48dir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(icon48dir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(icon48dir)" || exit $$?; \
	done

uninstall-icon48DATA:
	@$(NORMAL_UNINSTALL)
	@list='$(icon48_DATA)'; test -n "$(icon48dir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(icon48dir)'; $(am__uninstall_files_from_dir)
install-icon64DATA: $(icon64_DATA)
	@$(NORMAL_INSTALL)
	@list='$(icon64_DATA)'; test -n "$(icon64dir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(icon64dir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(icon64dir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(icon64dir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(icon64dir)" || exit $$?; \
	done

uninstall-icon64DATA:
	@$(NORMAL_UNINSTALL)
	@list='$(icon64_DATA)'; test -n "$(icon64dir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(icon64dir)'; $(am__uninstall_files_from_dir)
install-iconsDATA: $(icons_DATA)
	@$(NORMAL_INSTALL)
	@list='$(icons_DATA)'; test -n "$(iconsdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(iconsdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(iconsdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(iconsdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(iconsdir)" || exit $$?; \
	done

uninstall-iconsDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(icons_DATA)'; test -n "$(iconsdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(iconsdir)'; $(am__uninstall_files_from_dir)
install-pixmapDATA: $(pixmap_DATA)
	@$(NORMAL_INSTALL)
	@list='$(pixmap_DATA)'; test -n "$(pixmapdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(pixmapdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(pixmapdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(pixmapdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(pixmapdir)" || exit $$?; \
	done

uninstall-pixmapDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(pixmap_DATA)'; test -n "$(pixmapdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(pixmapdir)'; $(am__uninstall_files_from_dir)
tags TAGS:

ctags CTAGS:

cscope cscopelist:


distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(DATA)
installdirs:
	for dir in "$(DESTDIR)$(desktopdir)" "$(DESTDIR)$(icon128dir)" "$(DESTDIR)$(icon16dir)" "$(DESTDIR)$(icon32dir)" "$(DESTDIR)$(icon48dir)" "$(DESTDIR)$(icon64dir)" "$(DESTDIR)$(iconsdir)" "$(DESTDIR)$(pixmapdir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic mostlyclean-am

distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-generic

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-desktopDATA install-icon128DATA \
	install-icon16DATA install-icon32DATA install-icon48DATA \
	install-icon64DATA install-iconsDATA install-pixmapDATA

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-generic

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-desktopDATA uninstall-icon128DATA \
	uninstall-icon16DATA uninstall-icon32DATA uninstall-icon48DATA \
	uninstall-icon64DATA uninstall-iconsDATA uninstall-pixmapDATA

.MAKE: install-am install-strip

.PHONY: all all-am check check-am clean clean-generic cscopelist-am \
	ctags-am distclean distclean-generic distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-desktopDATA install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-icon128DATA install-icon16DATA install-icon32DATA \
	install-icon48DATA install-icon64DATA install-iconsDATA \
	install-info install-info-am install-man install-pdf \
	install-pdf-am install-pixmapDATA install-ps install-ps-am \
	install-strip installcheck installcheck-am installdirs \
	maintainer-clean maintainer-clean-generic mostlyclean \
	mostlyclean-generic pdf pdf-am ps ps-am tags-am uninstall \
	uninstall-am uninstall-desktopDATA uninstall-icon128DATA \
	uninstall-icon16DATA uninstall-icon32DATA uninstall-icon48DATA \
	uninstall-icon64DATA uninstall-iconsDATA uninstall-pixmapDATA


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
