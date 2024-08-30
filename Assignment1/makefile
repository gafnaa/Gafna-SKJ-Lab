all: to_asm

to_asm: to_asm.cpp
	g++ -o to_asm to_asm.cpp

dump: to_asm
	objdump -d to_asm > to_asm.cpp

clean:
	rm -f to_asm to_asm.asm

run: to_asm
	./to_asm