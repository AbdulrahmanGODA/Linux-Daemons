CC=gcc
CFLAGS=-Wall -pedantic -std=gnu99
all: markd copy
markd: main.c
	@$(CC) $(CFLAGS) main.c -o markd
copy: markd
	@sudo cp markd /usr/bin