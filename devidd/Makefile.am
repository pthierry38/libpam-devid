##
## Makefile.am for libpam-devid in /home/phil/Travail/Development/Pam/libpam-devid/src
##
## Made by Philippe THIERRY
## Login   <Philippe THIERRY@reseau-libre.net>
##
## Started on  mer. 20 juin 2012 15:30:31 CEST Philippe THIERRY
## Last update mer. 20 juin 2012 15:30:31 CEST Philippe THIERRY
##

SUBDIRS = .


bin_PROGRAMS = devidd

devidd_SOURCES = main.c
devidd_CFLAGS = ${AM_CFLAGS}

# options part
if EFENCE
devidd_LDADD = $(EFENCEFLAGS)
endif
#
EXTRA_DIST = 

CLEANFILES = *~ .*.swp .*.swo output* *.gcov *.gprof

