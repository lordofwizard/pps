# LordOfWizard's All PPS experiment answers
**WARNING THIS REPOSITORY IS A PRIVATE PROPERTY AND USED ONLY FOR EDUCATIONAL PURPOSES, ANY ACADEMIC ISSUES WILL BE YOUR OWN ISSUE lol**
* Experiment no 1
```py
gross_salary,basic,hra,ta,ptax = 0,0,10,5,2
basic = int(input("Please input your Monthly Salary :- "))
hra_amount = (hra * basic) / 100
ta_amount = (ta * basic ) / 100
ptax_amount = (ptax * basic ) / 100
total_tax = hra_amount + ta_amount + ptax_amount
net_salary = basic - total_tax

print(f"Your net salary for 1 year is {int(net_salary)}")
```
* Experiment no 2
```py
import math

n = int(input("Please input no of Numbers :- "))
n_copy = n
numbers = []
while n != 0:
    num = int(input())
    numbers.append(num)
    n = n - 1

print(f"minumum no in this list {min(numbers)}")
print(f"maximum no in this list {max(numbers)}")
print(f"sum no in this list {sum(numbers)}")
print(f"minumum no in this list {sum(numbers)/n_copy}")
```
* Experiment no 3
```py
N = int(input("Please enter N :- "))

SUM = 0
Number = N


while Number != 0:
    if Number != 0:
        SUM = (Number%10)**3 + SUM
        print(Number % 10)
        Number = Number // 10
        
    if N == SUM:
        print(f"N is an armstrong number")
        break
print(SUM)
```
* Experiment no 4
```py
def greet(name : str , msg : str):
    """This function greets to 
    the person with the provided message"""
    print("Hello",name + ',' + msg)

def add(num1 : int, num2 : int) -> int:
    """This function adds 2 ints called
    num1 and num2 and returns its output"""
    return num1 + num2

def sub(num1 : int, num2 : int) -> int:
    """This function substracts 2 ints called
    num1 and num2 and returns its output"""
    return num1 - num2

def mul(num1 : int, num2 : int) -> int:
    """This function multiplies 2 ints called
    num1 and num2 and returns its output"""
    return num1 * num2

def div(num1 : int, num2 : int) -> float:
    """This function divides 2 ints called
    num1 and num2 and returns its output"""
    return num1 / num2

def parser():
    """This function parses the given operator for the calculations
    And this function also takes 2 integer inputs to display result"""
    
    greet("Advait", "Welcome.. have a nice day")
    num1 = int(input("Please input number 1 :- "))
    if num1 == 0:
        print("DIsplay Error")
    
    op = input("Please input valid operator (+ , - , * , / ) :- ")
    num2 = int(input("Please input number 2 :- "))
    if num2 == 0:
        print("Display Error")
    
    if op == "+":
        print(add(num1,num2))
    if op == "-":
        print(sub(num1,num2))
    if op == "*":
        print(mul(num1,num2))
    if op == "/":
        print(add(num1,num2))
parser()
```
* Experiment no 5
```py
num = int(input("Please input number :- "))
rer = 0
while num > 0:
    rer = rer * 10 + num % 10
    num = num // 10
print("Reverse number is" ,rer)
```
* Experiment no 6
```py
  decimal = 0
base = 1

binary = int(input("Please input binary (10) no :- "))
while binary != 0:
    digit = binary % 10
    decimal = digit * base + decimal
    base = base * 2
    binary = binary // 10

print("Decimal number of given binary is",decimal)
```
* Experiment no 7
```py
f1 = 0
f2 = 1

n = int(input("Please input n :- "))
print ( f1,f2)
for i in range(0,n):
    f3 = f1 + f2
    print(f3)
    f1 = f2
    f2 = f3
```
* Experiment no 8
```py
import collections
import pprint
file_input = input("File name :- ")

with open(file_input,'r') as info:
    count = collections.Counter(info.read().upper())
    value = pprint.pformat(count)

print(value)
```
* NOTE you need to make a file and put it as input.. or it will give error

---
# JUST SAY LORDOFWIZARD IS THE BEST
![just gif](https://media.giphy.com/media/8kCwHHnkSnTO33NNQD/giphy.gif)
