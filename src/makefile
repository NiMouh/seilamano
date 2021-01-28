EXEC = main.exe
MainObject = main.o
FunctionObject = print-function.o

all: $(EXEC)
	./$(EXEC)
$(EXEC): $(MainObject) $(FunctionObject)
	gcc -o $@ $^
%.o: %.c
	gcc -c $^
clean:
	rm *.o
