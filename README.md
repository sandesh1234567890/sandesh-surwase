while True:
    print("select operator number")
    print("1 addition (+)")
    print("2 subtract (-)")
    print("3 multiply (x)")
    print("4 divide   (%)")

    choice = input("Enter operator=")

    if choice == "q" or choice == "Q":
        break
    num1 = float(input("Enter your number 1="))
    num2 = float(input("Enter your number 2="))
    if choice == "1":
        print(num1, "+", num2, "=", (num1+num2))

    elif choice == "2":
        print(num1, "-", num2, "=", (num1-num2))

    elif choice == "3":
        print(num1, "x", num2, "=", (num1*num2))

    elif choice == "4":
        print(num1, "%", num2, "=", (num1/num2))

    else:
        print("nothing")









