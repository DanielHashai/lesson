CC = gcc

prog: main.o min.o max.o
	$(CC) -o prog main.o min.o max.o
main.o: main.c Func.h
	$(CC) -c main.c
min.o: min.c Func.h
	$(CC) -c min.c
max.o: max.c Func.h
	$(CC) -c max.c
.PHONY: clean
clean:
	rm -f *.o prog
