all:
#	gcc mem_read.c -o mem_read -O0
#	gcc l1.c -o l1 -O0
#	gcc l2.c -o l2 -O0
#	gcc mem.c -o mem -O0

	gcc mem_read.c -lm -o mem -O0

test:
	./mem_read

clean:
	rm l1
	rm l2
	rm mem
