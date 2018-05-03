a.out: main.o Test.o
	g++ main.o Test.o
	rm *.o

Test.o: Test.h Test.cc
	g++ -c Test.cc

main.o: Test.h main.cc
	g++ -c main.cc
