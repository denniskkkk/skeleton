LDFLAGS = 
CFLAGS = 

all: testworld

testworld: testworld.o
	$(CC) $(LDFLAGS) testworld.o -o testworld

testworld.o: testworld.c
	$(CC) $(CFLAGS) -c testworld.c

clean: 
	rm *.o testworld