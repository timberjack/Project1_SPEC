
SOURCES= spec.c blocksort.c bzip2.c bzlib.c compress.c crctable.c \
	 decompress.c huffman.c randtable.c

CC=gcc
CFLAGS=-O0
COMP_FLAGS=-lm -DSPEC_CPU -DNDEBUG

all: $(SOURCES)
	$(CC) $(COMP_FLAGS) $(SOURCES) $(CFLAGS) -o benchmark



