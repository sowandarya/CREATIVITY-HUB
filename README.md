# CREATIVITY-HUB
def add(n1,n2):
return n1+n2
def sub(n1,n2):
return n1-n2
def multiply(n1,n2):
return n1*n2
def divide(n1,n2):
return n1/n2
def exponent(n1,n2):
return n1^n2
print("select operation:")
print("1.ADD")
print("2.SUB")
print("3.MULTIPLY")
print("4.DIVIDE")
print("5.EXPONENT")
choice=input("enter choice(1/2/3/4/5):")
n1=int(input("enter first number:"))
n2=int(input("enter second number:"))
if choice == "1" :
print(n1,"+",n2,"=",add(n1,n2))
elif choice == "2":
print(n1,"-",n2,"=",sub(n1,n2))
elif choice == "3"
print(n1,"*",n2,"=",multiply(n1,n2))
elif choice == "4"
print(n1,"/",n2,"=",divide(n1,n2))
elif choice == "5"
print(n1,"^",n2,"=",exponent(n1,n2))
else:
print("invalid input")
