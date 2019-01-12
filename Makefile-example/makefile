test.app : test.o logic.o
	c++ -o test.app test.o logic.o

test.o : test.cpp logic.hpp 
	c++ -c test.cpp logic.hpp 

logic.o : logic.hpp logic.cpp
	c++ -c logic.hpp logic.cpp

.PHONY : clean
clean :
	rm -f test.app test.o logic.o *.gch


