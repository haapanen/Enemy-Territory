#***************************************************************************
#                                  _   _ ____  _
#  Project                     ___| | | |  _ \| |
#                             / __| | | | |_) | |
#                            | (__| |_| |  _ <| |___
#                             \___|\___/|_| \_\_____|
#
# Copyright (C) 1998 - 2004, Daniel Stenberg, <daniel@haxx.se>, et al.
#
# This software is licensed as described in the file COPYING, which
# you should have received as part of this distribution. The terms
# are also available at http://curl.haxx.se/docs/copyright.html.
#
# You may opt to use, copy, modify, merge, publish, distribute and/or sell
# copies of the Software, and permit persons to whom the Software is
# furnished to do so, under the terms of the COPYING file.
#
# This software is distributed on an "AS IS" basis, WITHOUT WARRANTY OF ANY
# KIND, either express or implied.
#
# $Id: Makefile.am,v 1.7 2004/10/07 22:57:24 bagder Exp $
###########################################################################
# sws is the Silly Web Server
#
# Original http server code contributed by Georg Horn. Heavily modified since.
#

AUTOMAKE_OPTIONS = foreign

INCLUDES = -I$(top_srcdir)/lib -I$(top_srcdir)/include

noinst_PROGRAMS = sws

sws_SOURCES= sws.c getpart.c getpart.h $(top_srcdir)/lib/strequal.c

extra_DIST = config.h.in

