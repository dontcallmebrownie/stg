#OBJS specifies which files to compile as part of the project
OBJS = main.cpp ./lib/menus.cpp ./lib/inventory.cpp

#CC specifies which compiler we're using
CC = g++

#COMPILER_FLAGS specifies the additional compilation options we're using
# -w suppresses all warnings
COMPILER_FLAGS = -w

#LINKER_FLAGS specifies the libraries we're linking against
LINKER_FLAGS = 

#OBJ_NAME specifies the name of our exectuable
OBJ_NAME = ./bin/stg.lex

#This is the target that compiles our executable
default : $(OBJS)
	$(CC) $(OBJS) $(COMPILER_FLAGS) $(LINKER_FLAGS) -o $(OBJ_NAME)

run: 
	$(OBJ_NAME)
