#######################################
# The list of executables we are building seperated by spaces
# the 'bin_' indicates that these build products will be installed
# in the $(bindir) directory. For example /usr/bin
#bin_PROGRAMS=low_latency_object_pool_test

# Because a.out is only a sample program we don't want it to be installed.
# The 'noinst_' prefix indicates that the following targets are not to be
# installed.
noinst_PROGRAMS=low_latency_object_pool_test

#######################################
# Build information for each executable. The variable name is derived
# by use the name of the executable with each non alpha-numeric character is
# replaced by '_'. So a.out becomes a_out and the appropriate suffex added.
# '_SOURCES' for example.

ACLOCAL_AMFLAGS=-I ../m4

# Sources for the a.out 
low_latency_object_pool_test_SOURCES = low_latency_object_pool_test.cpp

# Libraries for a.out
#low_latency_object_pool_test_LDADD = $(top_srcdir)/libllmaloc/libllmaloc.la
low_latency_object_pool_test_LDADD =

# Linker options for a.out
# low_latency_object_pool_test_LDFLAGS = -rpath `cd $(top_srcdir);pwd`/libllmaloc/.libs
low_latency_object_pool_test_LDFLAGS = -lpthread

# Compiler options for a.out
low_latency_object_pool_test_CPPFLAGS = -I$(top_srcdir)/include -std=c++1y
