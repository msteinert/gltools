#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

# Initialize autoconf & automake
AC_PREREQ([2.67])
AC_INIT([GLTools], [193], [http://www.starstonesoftware.com/OpenGL/])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([1.9 foreign -Wno-portability])
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])
AC_CONFIG_SRCDIR([src/GLTools.cpp])

# Initialize libtool
LT_PREREQ([2.2])
LT_INIT([disable-static])

# Check for programs
AC_PROG_CXX

# Check for libraries
AC_CHECK_LIB([GL], [glClear])
AC_CHECK_LIB([GLU], [gluSphere])
AC_CHECK_LIB([X11], [XOpenDisplay])
AC_CHECK_LIB([glut], [glutCreateWindow])
AC_CHECK_LIB([m], [exp])

# Output files
AC_CONFIG_FILES([
	Makefile
	src/Makefile
])
AC_OUTPUT
