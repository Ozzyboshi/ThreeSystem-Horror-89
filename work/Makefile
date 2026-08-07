all:
	vasmm68k_mot -Fhunkexe -nosym -ldots -no-opt -wfail -o ./horror horror.s


	vasmm68k_mot -devpac -nocase -Fhunk   -o ./horror.o ./horror.s
	vlink -bamigahunk -o ./horror13 -s  ./horror.o

floppy:
	exe2adf -i horror13 -a horror13.adf