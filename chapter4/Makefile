CFLAGS = -Wno-implicit-int -Wno-return-type -Wall -g -pedantic -ansi -Werror

all: 4-01 4-02 rpn

4-01: 4-01.c
	cc $(CFLAGS) 4-01.c -o 4-01

4-02: 4-02.c
	cc $(CFLAGS) 4-02.c -o 4-02

rpn: rpn.c
	cc $(CFLAGS) rpn.c -o rpn

clean:
	rm -f 4-01 4-02 rpn

