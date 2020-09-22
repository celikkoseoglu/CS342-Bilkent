CC     = g++
CXX    = g++
LEX    = flex
PROG   = btree

all: $(PROG)

$(PROG): $(PROG).c
	$(CXX) -o $(PROG) $(PROG).c

test: $(PROG).c
	./$(PROG) in.txt out.txt

clean:
	-rm -f $(PROG)
