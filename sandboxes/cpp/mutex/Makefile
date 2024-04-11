CXX := g++
CXXFLAGS := -std=c++17 -Wall -Wextra -pthread

all: main

main: main.cpp
	$(CXX) $(CXXFLAGS) -o $@ $^

clean:
	rm -f main