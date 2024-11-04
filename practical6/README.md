This is practical 6 code

Step 6 compile:
gcc -c main.c
gcc -c matmult.c
gcc -o matmultC main.o matmult.o

execute:
./matmultC

output:

This is matrix A

   0   1   2
   1   2   3
   2   3   4
   3   4   5
   4   5   6

 This is matrix B

   0  -1  -2  -3
   1   0  -1  -2
   2   1   0  -1

 This is matrix C

   5   2  -1  -4
   8   2  -4 -10
  11   2  -7 -16
  14   2 -10 -22
  17   2 -13 -28

Step 7 Compilation using Makefile-

compile:
 make

result:
gcc  -c -O3 main.c
gcc  -c -O3 matmult.c
gcc  -o mmc main.o matmult.o -lm

execute:./mmc

output:

This is matrix A

   0   1   2
   1   2   3
   2   3   4
   3   4   5
   4   5   6

 This is matrix B

   0  -1  -2  -3
   1   0  -1  -2
   2   1   0  -1

 This is matrix C

   5   2  -1  -4
   8   2  -4 -10
  11   2  -7 -16
  14   2 -10 -22
  17   2 -13 -28
