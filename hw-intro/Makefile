CC?=gcc
CFLAGS?=-g
BINARIES=map limits

default:
	make map
	make limits

map: map.c
	i386-gcc $(CFLAGS) map.c recurse.c -o map

limits: limits.c
	i386-gcc $(CFLAGS) -Werror -Wall limits.c -o limits

clean:
	rm -f $(BINARIES)
