# Calculator
my second small project


a = int(input("Enter the first number:"))
b = int(input("Enter the second number:"))



print("1. Addition,+ 🥹")
print("2. Subtraction, - 🥹")
print("3. Multiplication, × 🥹")
print("4. Division, ÷ 🥹")

choice = input("choice:") 


if choice == "1":
    print(a+b)

elif choice == "2" :
    print(a-b)

elif choice == '23':
    print(a*b)

elif choice == "4":
    if b != 0 :
        print(a/b)

    else :
        print("Cannot be divided by zero")

else:
    print("Invald input")
