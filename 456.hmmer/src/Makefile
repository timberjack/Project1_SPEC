
SOURCES= alphabet.c core_algorithms.c debug.c display.c emit.c emulation.c \
	 fast_algorithms.c histogram.c hmmio.c hmmcalibrate.c hmmsearch.c \
	 mathsupport.c masks.c misc.c modelmakers.c plan7.c plan9.c postprob.c \
	 prior.c tophits.c trace.c ucbqsort.c a2m.c aligneval.c alignio.c \
	 clustal.c cluster.c dayhoff.c eps.c file.c getopt.c gki.c gsi.c \
	 hsregex.c iupac.c msa.c msf.c phylip.c revcomp.c rk.c selex.c \
	 seqencode.c shuffle.c sqerror.c sqio.c squidcore.c sre_ctype.c \
	 sre_math.c sre_random.c sre_string.c ssi.c stack.c stockholm.c \
	 translate.c types.c vectorops.c weight.c

CC=gcc
CFLAGS=-O0
COMP_FLAGS=-DSPEC_CPU -DNDEBUG -static

all: $(SOURCES)
	$(CC) $(COMP_FLAGS) $(SOURCES) $(CFLAGS) -o benchmark -lm



