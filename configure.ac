#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ(2.59)
AC_INIT(libg15, 1.3, mlampard@users.sourceforge.net)
AM_INIT_AUTOMAKE([check-news foreign 1.9 dist-bzip2])
AC_PREFIX_DEFAULT([/usr])

AM_INIT_AUTOMAKE()
AC_CONFIG_SRCDIR([libg15.c])
AC_CONFIG_HEADER([config.h])

# Checks for programs.
AC_PROG_CC
AC_PROG_LIBTOOL

# Checks for libraries.
PKG_CHECK_MODULES(LIBUSB, libusb-1.0 >= 1.0.0)


# Checks for header files.
AC_HEADER_STDC
AC_CHECK_HEADERS([string.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_C_CONST

# Checks for library functions.
AC_CHECK_FUNCS([memset])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
