all : prog_tp6

rebuild : clean all

prog_tp6 : mainCompte.o compte.o
	g++ -o prog_tp6 mainCompte.o compte.o -g

mainCompte.o : ../mainCompte.cpp
	g++ -o mainCompte.o -c ../mainCompte.cpp -g

compte.o : ../compte.cpp
	g++ -o compte.o -c ../compte.cpp -g

clean :
	del *.o