# Calculator
try:
    first_number=float(input("enter the first number:"))
    second_number=float(input("enter the second number:"))
    operator=input("please enter the operator:")
    if operator=="+":
        print(first_number+second_number)
    elif operator=="-":
        print(first_number-second_number)
    elif operator=="*":
        print(first_number*second_number)
    elif operator=="/":
        print(first_number/second_number)
    elif operator=="%":
        print(first_number%second_number)
    else:
        print("invalid input")
except ValueError:
    print("invalid input number")
except ZeroDivisionError:
    print("zero division is not possible")
