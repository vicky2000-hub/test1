"""2.	First create a range from 1 to 8. Then using zip, merge the given list and the range together to create a new list of tuples."""
import operator 
from functools import reduce


def countList(l1,l2): 
	x= tuple(reduce(operator.add, zip(l1,l2))) 
	return x
l1=[]
l2=['my','name','is','S.VIGNESH','NICE','to','meet','you']
for i in range(1,9):
    l1.append(i)

print(countList(l1, l2)) 
    
