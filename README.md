3)Write a program to print all the even numbers till 100 by adjacent values using while loop.


loop=1
n=100
while loop<=n:
    if loop%2==0:
        print(loop,end='\t')
    loop+=1
