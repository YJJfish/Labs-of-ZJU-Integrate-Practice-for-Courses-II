CC=gcc
SOURCES=compute.c input.c main.c
HEADERS=compute.h input.h main.h
OBJECTS=compute.o input.o main.o
power: $(OBJECTS)
	$(CC) $(OBJECTS) -o power -lm
main.o: main.c $(HEADERS)
	$(CC) -c main.c -o main.o
compute.o: compute.c compute.h
	$(CC) -c compute.c -o compute.o
input.o: input.c input.h
	$(CC) -c input.c -o input.o

