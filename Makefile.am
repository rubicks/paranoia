# paranoia/Makefile.am

ACLOCAL_AMFLAGS = -I m4

AM_CPPFLAGS = -DNOPAUSE

AM_CFLAGS =          \
  -ansi              \
  -Wall              \
  -Wextra            \
  -Wpedantic         \
  -Werror            \
  -Wconversion       \
  -Wdouble-promotion

bin_PROGRAMS = paranoia

paranoia_SOURCES = paranoia.c

check_PROGRAMS = $(bin_PROGRAMS)

TESTS = $(check_PROGRAMS)

