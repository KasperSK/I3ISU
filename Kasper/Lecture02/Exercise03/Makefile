SOURCES=main.cpp part1.cpp part2.cpp
OBJECTS=${SOURCES:.cpp=.o}
EXECUTABLE=main
CXX=g++

all: ${OBJECTS}
	  @${CXX} -o ${EXECUTABLE} ${OBJECTS}

%.o: %.cpp
	@${CXX} -c -o $@ $^

clean: 
	@rm -f ${EXECUTABLE} ${OBJECTS}

help:
	@echo "Targets:"
	@echo "  all"
	@echo "  clean"
	@echo "  help"
	@echo ""
	@echo "Vars:"
	@echo "  CXX"
	@echo "  EXECUTABLE"
	@echo "" 
