# compiler
CC = gcc
# flags
CFLAGS = -Wall -g
# general dependencies
DEPS = item.h st.h
# object files
OBJ = main.o item.o st.o
# main file name
TARGET = main
# out file name
OUT = out
# standard
STD = -std=c99


all : $(TARGET) 

$(TARGET): $(OBJ)
	gcc $(CFLAGS) $(STD) -o $(OUT) $(OBJ) -lm

$(OBJ): $(DEPS)

.PHONY : clean
clean:
	rm -rf $(wildcard *.o) $(wildcard *~) out
