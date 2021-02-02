# Makefile to compile demverifier.c

CC=cc
LIBS=-lgdal

pitremove_verifier: demverifier.c
	$(CC) demverifier.c $(LIBS) -o demverifier -I$(GDAL_HOME)/include -L$(GDAL_HOME)/lib
	
clean:
	rm -f demverifier

