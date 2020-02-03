pyramid: stuff.o themainprog.o
	gcc -o pyramid stuff.o themainprog.o
stuff.o: stuff.c stuff.h
	gcc -c stuff.c
themainprog.o: themainprog.c stuff.h
	gcc -c themainprog.c
clean:
	rm -f pyramid stuff.o themainprog.o