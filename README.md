#prime number cheack
Num=input()
Num=int(Num)
for i in range (2,Num):
    if(Num%i == 0):
         break
    else:
         print (Num , "is prime") 
