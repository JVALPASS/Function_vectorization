# (c) 2010 The Board of Trustees of the University of Illinois

LANGUAGE=c
TOOLS_SRC=common_src/convert-dataset
SRCDIR_OBJS=main.o file.o 
APP_CFLAGS=-I$(TOOLS_SRC)
APP_CFLAGS += -O2 -mavx2 -fopenmp-simd -S
include $(TOOLS_SRC)/commontools.mk