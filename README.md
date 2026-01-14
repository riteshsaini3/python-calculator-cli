# python-calculator-cli

while True:
    num1 = int(input("Enter first number: "))
    num2 = int(input("Enter second number: "))
    choice = input("Enter operation (+, -, *, /, %): ")

    if choice == "+":
        sum_of_numbers = num1 + num2
        print("The sum is:", sum_of_numbers)
    elif choice == "-":
        difference_of_numbers = num1 - num2
        print("The difference is:", difference_of_numbers)
    elif choice == "*":
        product_of_nmbers = num1 * num2
        print("The product is:", product_of_nmbers)
    elif choice == "/":
        division_of_numbers = num1 / num2
        print("The division is:", division_of_numbers)
    elif choice == "%":
        modulus_of_numbers = num1 % num2
        print("The modulus is:", modulus_of_numbers)
    else:
        print("Invalid operation")
        quit_choice = input("Do you want to quit? (yes/no): ") 
    quit_choice = input("Do you want to quit? (yes/no): ")
    if quit_choice.lower() == "yes":
        break
    
        