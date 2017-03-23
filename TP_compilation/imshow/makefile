all : imshow.out

sayHello.out : imshow.o
	g++ -o imshow.out imshow.o

imshow.o : imshow.cpp 
	g++ -c -std=c++11 imshow.cpp

clean : rm -f imshow.out
