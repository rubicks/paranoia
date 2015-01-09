# paranoia/configure.ac

AC_PREREQ([2.68])

AC_INIT([paranoia],
        [0.1.0],
        [rubicks00@gmail.com],
        [paranoia],
        [https://github.com/rubicks/paranoia])

AC_CONFIG_MACRO_DIR([m4])
AC_LANG_PUSH([C])
AM_INIT_AUTOMAKE([subdir-objects])
LT_PREREQ([2.4])
LT_INIT([dlopen])
AC_CONFIG_SRCDIR([paranoia.c])

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_LN_S

# Checks for libraries.
AC_CHECK_LIB([m],[floor])

# Checks for header files.
#AC_HEADER_STDC # stdlib.h stdarg.h string.h float.h
AC_CHECK_HEADERS([stdio.h signal.h],,,[AC_INCLUDES_DEFAULT])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
dnl AC_CHECK_LIB([m],[pow])
dnl AC_CHECK_LIB([m],[sqrt])
AC_CHECK_FUNCS([floor pow sqrt])

AC_CONFIG_FILES([Makefile])

AC_CONFIG_HEADERS([config.h])

AC_OUTPUT
