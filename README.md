# Maximum-Number
#To find the Maximum of three numbers
n1=int(input("Enter n1:"))
n2=int(input("Enter n2:"))
n3=int(input("Enter n3:"))
if n1>n2 & n1>n3:
    print(n1,"is largest")
elif n2>n1 & n2>n3:
    print(n2,"is largest")
else:
    print(n3,"is largest")

