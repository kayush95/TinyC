a.out:	compiler_assembly_print.o ass6_13CS10058_test.o
	cc -m32 ass6_13CS10058_test.o compiler_assembly_print.o

compiler_assembly_print.o: 	compiler_assembly_print.c myl.h
	cc -c -m32 compiler_assembly_print.c

ass6_13CS10058_test.o: 		ass6_13CS10058_test.s
	cc -c -m32 ass6_13CS10058_test.s -o ass6_13CS10058_test.o

clean:
	rm ass6_13CS10058_test.o compiler_assembly_print.o a.out
