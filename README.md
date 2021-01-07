#Practice Problems based on if else and loops:

#Program to print the sum upto a given number input by the user
a=int(input("enter the number upto which you want the sum \n"))
c=0
for i in range(a+1):
    c=c+(a-i)
print(c)

#Program to display numbers in a list which are divisible by 5 and if you find number greater than 150 stop the loop iteration
list1 = [12, 15, 32, 42, 55, 75, 122, 132, 150, 180, 200]
for i in range(len(list1)):
    if list1[i]>150:
        break
    if list1[i]%5==0:
        print(list1[i])

#count the numbers of digit in a given number        
a=75869
c=0
while a!=0:
    a=a//10
    c=c+1
print(c)
