CC = gcc
CFLAGS = -g -Wall
.PHONY: clean
libfuncs.a: func1.o func2.o
	ar rv libfuncs.a func1.o func2.o 
func1.o: func1.c
	$(CC) -c func1.c -o func1.o
func2.o: func2.c
	$(CC) -c func2.c -o func2.o

clean:
	rm *.o
