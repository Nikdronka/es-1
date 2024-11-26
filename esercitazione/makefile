all: main

clean: main main.o es.o
	rm -rf main main.o es.o

main: main.o es.o
	gcc -o main main.o es.o

main.o: main.c potenze.h 
	gcc -c -o main main.o 

es.o: es.c potenze.h
	gcc -c -o es.o es.c