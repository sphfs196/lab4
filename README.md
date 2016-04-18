lab4.A:
00000000004004b4 T _Z7averagePdRd
00000000004004e2 T _Z7averageif

These two are used for the functions.
explanation:
nm:print the object's symbol-->two functions have the same name average.
							-->g++ differentiate the two by the argument's type name while								compiling.
							-->function overloading:
								the first one's arguments' type are 
								(double*,double&), so the new name is averagePdRd
								(Pd:pointer double)(Rd:referance double).
								
								the second one's arguments' type are
								(int,float), so the new name is averageif
								(i:int)(f:float)

lab4.B
the output of the program:
1       8
4       8
4       8
8       8

1 4 4 8 : the memory that every variable used.(-->char :1byte/int :4byte/float :4byte/double :8byte)

8 8 8 8 : the memory that the pointer used.8byte is because of the 64-bit computer.
