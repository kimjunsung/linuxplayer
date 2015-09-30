.PHONY: clean
player: player.o
	gcc -o player -L../lib player.o -lfuncs
player.o: player.c
	gcc -g -Wall -c player.c -o player.o
clean:
	rm *.o
