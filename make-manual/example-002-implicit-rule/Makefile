objects = main.o carg_parser.o main_loop.o global.o signal.o regex.o buffer.o io.o

# declare clean targe is phony target
.PHONY: clean

edit : $(objects)
	cc -o edit $(objects)

main.o : carg_parser.h ed.h
carg_parser.o : carg_parser.h
main_loop.o : ed.h
global.o : ed.h
signal.o : ed.h
regex.o : ed.h
buffer.o : ed.h
io.o : ed.h

clean :
	rm edit main.o carg_parser.o main_loop.o global.o signal.o regex.o buffer.o io.o