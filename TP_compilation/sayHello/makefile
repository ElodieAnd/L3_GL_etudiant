all : sayHello.out

sayHello.out : module1.o sayHello.o
	g++ -o sayHello.out module1.o sayHello.o

module1.o : module1.cpp 
	g++ -c -g -std=c++11 module1.cpp

sayHello.o : sayHello.cpp 
	g++ -c -g -std=c++11 sayHello.cpp

clean : rm-f module1.out sayHello.out
