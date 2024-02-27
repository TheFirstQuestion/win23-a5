calculator: main.o addition.o subtraction.o multiplication.o division.o
	gcc -o calculator main.o addition.o subtraction.o multiplication.o division.o operations.h

calculator.o: main.c
	gcc -c main.c

clean: 
	rm -f calculator *.o
