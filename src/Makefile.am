#                                        -*- Automake -*-
# Process this file with automake to produce Makefile.in.

lib_LTLIBRARIES = libgltools.la

libgltools_la_SOURCES = \
	GLBatch.cpp \
	GLShaderManager.cpp \
	GLTriangleBatch.cpp \
	math3d.cpp \
	glew.c \
	GLTools.cpp

libgltools_la_CPPFLAGS = \
	-I$(top_srcdir)/include \
	-I$(top_srcdir)/include/GL

pkgincludedir = $(includedir)/GLTools
pkginclude_HEADERS = \
	$(top_srcdir)/include/GLShaderManager.h \
	$(top_srcdir)/include/GLBatch.h \
	$(top_srcdir)/include/GLMatrixStack.h \
	$(top_srcdir)/include/GLFrame.h \
	$(top_srcdir)/include/GLGeometryTransform.h \
	$(top_srcdir)/include/GLTools.h \
	$(top_srcdir)/include/GLFrustum.h \
	$(top_srcdir)/include/math3d.h \
	$(top_srcdir)/include/GL/glew.h \
	$(top_srcdir)/include/GL/glxew.h \
	$(top_srcdir)/include/GL/wglew.h \
	$(top_srcdir)/include/GLTriangleBatch.h \
	$(top_srcdir)/include/StopWatch.h \
	$(top_srcdir)/include/GLBatchBase.h
