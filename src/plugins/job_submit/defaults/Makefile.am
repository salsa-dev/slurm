# Makefile for job_submit/defaults plugin

AUTOMAKE_OPTIONS = foreign

PLUGIN_FLAGS = -module -avoid-version --export-dynamic

INCLUDES = -I$(top_srcdir) -I$(top_srcdir)/src/common

pkglib_LTLIBRARIES = job_submit_defaults.la

# Job submit defaults plugin.
job_submit_defaults_la_SOURCES = job_submit_defaults.c
job_submit_defaults_la_LDFLAGS = $(SO_LDFLAGS) $(PLUGIN_FLAGS)
