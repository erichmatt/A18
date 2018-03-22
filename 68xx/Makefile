CC=gcc
A68SRC=a68.c  a68eval.c  a68util.c
A68H=a68.h
DEFS= -DMODERN $(ADEF)

a18: $(A68SRC) $(A68H)
	$(CC) -o a68 $(DEFS)  $(A68SRC) 

clean:
	rm a68
