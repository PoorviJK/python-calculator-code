#calculator
first = float(input("enter first number"))
operations = input("enter operator(+,-,/,*)")
second = float(input("enter second number"))

if operations == "+" :
    print(first + second)


elif operations == "-" :
    print(first - second)


elif operations == "/" :
    print(first / second)


elif operations == "*" :
    print(first * second)


else:
    print("IVALID OPERATOIN!!!")
