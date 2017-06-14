all: COMMISSION symbolicExecution.cpp
	clang++ -emit-llvm -c -g -o symbolicExecution.o symbolicExecution.cpp
	llvm-link -o symbolicExecutionCommission.bc symbolicExecution.o commission.o
COMMISSION: ../commission.h ../commission.cpp
	clang++ -emit-llvm -c -g -o commission.o ../commission.cpp
