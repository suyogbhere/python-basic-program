# python-basic-program
Practice python program
a number that can be divided exactly only by itself and 1
 
n=int(input ("enter the number:")
if n<=1:
    for i in range(2,n):
        if n%i==0:
            print ("Not Prime number")
        else:
            print ("it is prime numbers")
else:
    print ("Not a prime number")
