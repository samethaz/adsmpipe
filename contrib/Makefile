#
# File:        Makefile
# Program:     adsmpipe
# 
#

CFLAGS=-g
LPATH=.

FILES=adsmpipe.c adsmblib.c

all:		adsmpipe

adsmpipe:	$(FILES:.c=.o)
	$(CC) -o $@ $(FILES:.c=.o) -lApiDS -L$(LPATH)
	rm *.o

SRCFILES=$(FILES) Makefile libApiDS.a dsmapifp.h  dsmapitd.h  dsmrc.h

