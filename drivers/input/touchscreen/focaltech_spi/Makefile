#
# Makefile for the focaltech touchscreen drivers.
#

ccflags-y += -DDEBUG

obj-m += focaltech_spi_ts.o

focaltech_spi_ts-objs := focaltech_core.o \
	focaltech_ex_fun.o \
	focaltech_ex_mode.o \
	focaltech_gesture.o \
	focaltech_esdcheck.o \
	focaltech_point_report_check.o \
	focaltech_spi.o \
	focaltech_flash.o \
	ts_func_test.o
