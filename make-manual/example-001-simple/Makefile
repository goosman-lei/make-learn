# declare clean targe is phony target
.PHONY clean

edit : main.o carg_parser.o main_loop.o global.o signal.o regex.o buffer.o io.o
	cc -o edit main.o carg_parser.o main_loop.o global.o signal.o regex.o buffer.o io.o

main.o : main.c carg_parser.h ed.h
	cc -c main.c

carg_parser.o : carg_parser.c carg_parser.h
	cc -c carg_parser.c

main_loop.o : main_loop.c ed.h
	cc -c main_loop.c

global.o : global.c ed.h
	cc -c global.c

signal.o : signal.c ed.h
	cc -c signal.c

regex.o : regex.c ed.h
	cc -c regex.c

buffer.o : buffer.c ed.h
	cc -c buffer.c

io.o : io.c ed.h
	cc -c io.c

clean :
	rm edit main.o carg_parser.o main_loop.o global.o signal.o regex.o buffer.o io.o