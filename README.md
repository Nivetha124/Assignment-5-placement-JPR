# Assignment-5-placement-JPR
# 1) Fibonacci series

def fibonacci(num):
    if num==0:
        return 0
    elif num==1:
        return 1
    else:
        return fibonacci(num-2)+fibonacci(num-1)
n=7
for i in range(0,n):
    print(fibonacci(i),end=" ")
                                                  (OR)
def printFibonacciNumbers(n):
    n1=0
    n2=1
    if n<1:
        return
    print(n1, end=" ")
    for x in range(1,n):
        print(n2,end=" ")
        next=n1+n2
        n1=n2
        n2=next
printFibonacciNumbers(7)
                                                  (OR)
nterms = int(input("How many terms? "))
n1, n2 = 0, 1
count = 0
if nterms <= 0:
   print("Please enter a positive integer")
elif nterms == 1:
   print("Fibonacci sequence upto",nterms,":")
   print(n1)
else:
   print("Fibonacci sequence:")
   while count < nterms:
       print(n1)
       nth = n1 + n2
       n1 = n2
       n2 = nth
       count+=1

# 2) Find the Nth Fibonacci number Input:7 /Output:8

def Fibonacci(n):
    if n <= 0:
        print("Incorrect input")
    # First Fibonacci number is 0
    elif n == 1:
        return 0
    # Second Fibonacci number is 1
    elif n == 2:
        return 1
    else:
        return Fibonacci(n - 1) + Fibonacci(n - 2)
print(Fibonacci(7))

# 3) 1)Print N asterisks(*) Input /Output 5 *****

x= int(input("enter the number of asterids"))
for i in range(0,x):
    print("*",end="")

# 3) 2)Print X lines of “Hi” Input X=4 ,O/p Hi
                                            Hi
                                            Hi
                                            Hi

x=int(input("enter the number of x will be excute"))
for i in range(0,x):
    print("Hi")
    
# 4)Print X lines ,in each line contains its line number Input :5 Output: 1 2 3 4 5

x=int(input("enter the number"))
for i in range(1,x+1):
    print(i)
    
# 5) Print X lines ,in each line should be the square of the line number Input: 5 O/P : 1 4 9 16 25

x=int(input("enter the number"))
for i in range(1,x+1):
    print(i**2)
    
# 6) Print X lines ,in each line should be ODD numbers starting from 1.Input: X= 4 O/P: 1 3 5 7

x=int(input("enter the number"))
for i in range(1,x*2):
    if i%2 != 0:
        print(i)
                                                (OR)
x=int(input("enter the number"))
for i in range(1,x*2,2):
    print(i)
    
# 7) Get a number N, print 1toN without space. I/P:6 O/P 123456
x=int(input("enter the number"))
for i in range(1,x+1):
    print(i,end='')
  

