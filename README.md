# while_3.py
#program to find the factors of whole number using while loop
#i is factor for every number
#2 is factor if its not prime
#we check till num/2 is sufficent to get factors for  any  number
#as well as finding number also factor of itself


num=int(input("enetr the number to be find its factor:"))
print(1,end=' ')
factor=2
while factor<=num/2:  #after num/2 the loop will terminate
    if num%factor==0:
        print(factor,end=" ")
    factor +=1
print(num,end =" ")
    
