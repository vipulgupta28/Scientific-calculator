# Scientific-calculator
This calculator is made using python programming language. i am uploading the code with full details


CODE:

import math
calculator=True
while calculator:
    c=input("Do you want to Use the caluclator y? : Y/N\n")
    if c=="N":
        break
    print("<<<<>>>>\n Press \n 1-Addition(x,y) \n 2-Subtraction(x,y) \n 3-Multiplication(x,y) \n 4-Division(x,y) \n 5-Exponenet(x,y) \n 6-Sin(x,y) \n 7-Tan(x,y) \n 8-Cos(x,y) \n 9-Convert to radian \n 10-Convert radian to degree \n<<<<>>>>")
    x=int(input("Enter Your choice: "))
    if x==1:
        a=int(input("Enter your first number: "))
        b=int(input("Enter the second number: "))
        print(a+b)
    elif x==2:
        a=int(input("Enter your first number: "))
        b=int(input("Enter the second number: "))
        print(a-b)
    elif x==3:
         a=int(input("Enter your first number: "))
         b=int(input("Enter the second number: "))
         print(a*b)
    elif x==4:
        a=int(input("Enter your first number: "))
        b=int(input("Enter the second number: "))
        print(a/b)
    elif x==5:
        a=int(input("Enter your first number: "))
        b=int(input("Enter the second number: "))
        print(a**b)
    elif x==6:
        a=int(input("Enter the value for angle: "))
        print(math.sin(a))
    elif x==7:
        a=int(input("Enter The value for angle: "))
        print(math.tan(a))
    elif x==8:
        a=int(input("Enter the value for angle: "))
        print(math.cos(a))
    elif x==9:
        a=int(input("Enter the angle: "))
        print(math.radians(a))
    elif x==10:
        a=int(input("Enter the angle in radian: "))
        print(math.degrees(a))
    else:
        print("Invalid input")
