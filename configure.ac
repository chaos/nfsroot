##
# Prologue
##
AC_INIT(m4_esyscmd([awk '/Name:/ {printf "%s",$2; exit}' META]),
        m4_esyscmd([awk '/Version:/ {printf "%s",$2; exit}' META]))
AC_CONFIG_AUX_DIR([config])
AC_CONFIG_SRCDIR([NEWS])
AC_CANONICAL_SYSTEM
X_AC_META
X_AC_EXPAND_INSTALL_DIRS

##
# Automake support
##
AM_INIT_AUTOMAKE([])
AC_CONFIG_HEADERS([config/config.h])
AM_MAINTAINER_MODE

##
# Epilogue
##
AC_CONFIG_FILES( \
  nfsroot.spec \
  Makefile \
  boot/Makefile \
  configpxe/Makefile \
  configpxe/configpxe.8 \
  etc/Makefile \
  freedos/Makefile \
  rc/Makefile \
  dracut/Makefile \
  dracut.nbd9/Makefile \
)

AC_OUTPUT
