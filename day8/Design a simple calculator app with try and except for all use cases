"""Design a simple calculator app with try and except for all use cases"""

operator_set = set(["+", "add", "addition",
            "-", "subtract", "subtraction",
            "/", "divide", "division",
            "x", "*", "multiply", "multiplication"])
try:
    num1 = int(input("Enter first number: "))
    num2 = int(input("Enter second number: "))
    calculation = input("How would you like t calulate this?\n").lower()
except Exception as e:
    print("Error : {}".format(str(e)))
else:
    if calculation in operator_set:
        pass
    else:
        print("Please re-enter a valid operator!")

def add():
    sum1=num1+num2
    print(sum1)
def sub():
    sum1=num1-num2
    print(sum1)
def mul():
    sum1=num1*num2
    print(sum1)
def div():
    sum1=num1/num2
    print(sum1)

if calculation in ["+","add"]:
    add()
if calculation in ["-","sub"]:
    sub()
if calculation in ["*","mul"]:
    mul()
if calculation in ["/","div"]:
    div()
    
