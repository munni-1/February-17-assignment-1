 1#PROGRAM TO PRINT SUM OF ODD AND EVEN NUMBERS
n=int(input("enter number range:"))
sum=0
total=0
for i in range (1,n+1):
    if i%2==1:
        sum=sum+i
    if i%2==0:
        total=total+i
sum=sum+total
print('sum of even and odd numbers :' ,sum)

OUTPUT:
enter number range:10
sum of even and odd numbers : 55
