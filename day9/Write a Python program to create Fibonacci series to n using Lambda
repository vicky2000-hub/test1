"""Write a Python program to create Fibonacci series to n using Lambda"""


from functools import reduce

i=int(input("enter the number you need to fabric"))
fib = lambda n: reduce(lambda x, _: x+[x[-1]+x[-2]],range(n-2), [0, 1])
print(fib(i))
