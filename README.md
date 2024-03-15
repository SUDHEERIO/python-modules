# python-modules
1).
import math
pie=math.pi
print("the value of pie: ",pie)


2).
from math import pi
print(pi)

3).
import math as m
result=m.sqrt(25)
print("square root of 25:",result)

4).
from math import*
print(pi)
print(factorial(5))
print(sqrt(36))

5).
import random
random_number=random.randint(1,10)
print("Random Number:",random_number)

6).
import random
passlen=int(input("enter the length of password:"))
s="jhfurtyv"
p="".join(random.sample(s,passlen))
print(p)

7).
#system module
import sys
print(sys.path)
