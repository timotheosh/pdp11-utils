# Makefile for env program for BSD 2.11 on PDP-11
all: env.o
	cc -o env env.o -lerrlst

env.o:
	cc -c env.c

clean:
	rm -f env *.o
