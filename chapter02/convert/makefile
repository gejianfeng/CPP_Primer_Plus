CC = g++

convert: convert.o
	$(CC) -o convert convert.o

convert.o: convert.cpp
	$(CC) -c convert.cpp

clean:
	rm -rf *.o convert