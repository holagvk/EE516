CC=gcc
CFLAGS=-Wall -Werror -g
LDFLAGS=-lpthread
BIN=read_write

all: $(BIN)

$(BIN):
	$(CC) -o $@ $@.c $(CFLAGS) $(LDFLAGS)

clean:
	rm -f $(BIN)
