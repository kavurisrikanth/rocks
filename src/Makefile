CC = g++
TARGET = Catalog
OBJ = IOHandler.o Catalog.o
COMPILE_FLAGS = -g -std=c++1y -pthread
BUILD_FLAGS = -lpthread
DEPS = common.hh

%.o: %.cc
	$(CC) -c $(COMPILE_FLAGS) -o $@ $<

$(TARGET): $(OBJ)
	$(CC) -o $@ $^ $(BUILD_FLAGS)