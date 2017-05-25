CC = mpicc
all:
	$(CC) dotproduct.c -o dotproduct.x

extra:
	$(CC) extra_dotproduct.c -o extra_dotproduct.x

allreduce:
	$(CC) dotproduct_reduceAll.c -o dotproduct_reduceAll.x

serial:	
	gcc serial_dotproduct.c -o serial_dotproduct.x
