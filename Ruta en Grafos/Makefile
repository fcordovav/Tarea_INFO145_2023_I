CC = g++
CFLAGS = -std=c++17 -O3
SOURCES = solucionGrafos.cpp
EXECUTABLE = prog2

all: $(EXECUTABLE)

$(EXECUTABLE): $(SOURCES)
	$(CC) $(CFLAGS) $^ -o $@

clean:
	rm -f $(EXECUTABLE)
