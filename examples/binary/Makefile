CXX=c++
CC=cc
CFLAGS += -O2 -Wall -W
CXXFLAGS += -O2 -Wall -W

TARGETS=binaryC binaryCpp binaryCpp2 binaryCpp3

all: binaryC.o binaryCpp.o binaryCpp2.o binaryCpp3.o
	$(CC) $(CFLAGS) -o binaryC binaryC.o -lm
	$(CXX) $(CXXFLAGS) -o binaryCpp binaryCpp.o
	$(CXX) $(CXXFLAGS) -o binaryCpp2 binaryCpp2.o
	$(CXX) $(CXXFLAGS) -o binaryCpp3 binaryCpp3.o

clean:
	rm -f *.o $(TARGETS)
