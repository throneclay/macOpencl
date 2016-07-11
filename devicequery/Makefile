cc=clang
cflags=-framework OpenCL
prog=main

$(prog): main.c
	$(cc) $(cflags) -o $@ $<

run: $(prog)
	./$(prog)

clean:
	rm -rf $(prog)
