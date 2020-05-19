SRC = src
INC = include
OBJ = obj
BIN = bin

CXX = g++
CPPFLAGS = -O2 -Wall -g -I./$(INC) -std=c++11


all: $(BIN)/binPacking

$(BIN)/binPacking : $(SRC)/main.cpp $(INC)/Problema.h $(SRC)/Problema.cpp $(INC)/Solucion.h $(SRC)/Solucion.cpp $(INC)/Algoritmos.h $(SRC)/Algoritmos.cpp
	$(CXX) $(CPPFLAGS) -o $(BIN)/binPacking $(SRC)/main.cpp


# ************ Limpieza ************
clean :
	-rm $(OBJ)/* $(SRC)/*~ $(INC)/*~ ./*~

mrproper : clean
	-rm $(BIN)/* 


