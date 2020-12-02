"""Write a Python program to search the numbers (0-9) of length between 1 to 3 in a given string"""


import re
x=input("enter the number")
results = re.finditer(r"([0-9]{1,3})",x)
print("Number of length 1 to 3")
for n in results:
     print(n.group(0))
