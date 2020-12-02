"""Write a Python program that matches a word containing 'ab'."""


def text_match(text):
        patterns = '^ab$'
        patterns1= 'a.*?b$'
        if re.search(patterns,  text):
                return (text,'result found')
        elif re.search(patterns1,  text):
                return (text,'result found')
        else:
                return('Not matched!')


x=input("enter the string")
print(text_match(x))
