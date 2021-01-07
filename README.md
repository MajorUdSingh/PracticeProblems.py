#Program to print the sum upto a given number input by the user
a=int(input("enter the number upto which you want the sum \n"))
c=0
for i in range(a+1):
    c=c+(a-i)
print(c)
