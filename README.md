def add(x, y):
    return x + y

def divide(x, y):
    if y == 0:
        return "Cannot divide by zero!"
    return x / y

def multiply(x, y):
    return x * y

def subtract(x, y):
    return x - y


def main():
   
    print("Select option:")
    print("a. Add","b. Divide","c. Multiply","d.subtract",)
   
    choice = input("Enter choice (a/b/c/d): ")

    num1 = int(input("Enter first number: "))
    num2 = int(input("Enter second number: "))

    if choice == 'a':
        sum=num1+num2
        print(sum)

    elif choice == 'b':
        div=num1/num2
        print(div)

    elif choice == 'c':
        mul=num1*num2
        print(mul)

    elif choice == 'd':
        sub=num1-num2
        print(sub)

    else:
        print("invalid input ")
    
if __name__ == "__main__":
    main()


