"""1.	Write a program using zip() function and list() function, create a merged list of tuples from the two lists given."""
import operator 
from functools import reduce

def countList(lst1, lst2): 
	x= tuple(reduce(operator.add, zip(lst1, lst2))) 
	return x
lst1 = [1, 2, 3,323,424,3,434,424324] 
lst2 = ['a',1,231,34,2, 'b', 'c'] 
print(countList(lst1, lst2)) 
