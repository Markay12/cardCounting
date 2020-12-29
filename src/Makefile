main: cardCount.o Cards.o BagNode.o
	g++ -g -Wall cardCount.o Cards.o BagNode.o -o main

cardCount.o: cardCount.cpp Cards.h BagNode.h
	g++ -g -Wall cardCount.cpp -c 

Cards.o: Cards.cpp  Cards.h
	g++ -g -Wall Cards.cpp BagNode.cpp -c

BagNode.o: BagNode.cpp BagNode.h
	g++ -g -Wall BagNode.cpp -c

clean:
	rm *.o main 
