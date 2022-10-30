height = float(input("Enter your height in inches: "))

weight = float(input("Enter your weight in lbs: "))

BMI = weight * 703 / (height ** 2)

print("Your Body Mass Index is ",BMI)

if BMI > 0:
    
     if BMI <= 16:
        print("You are severely underweight")

    elif BMI <= 18:
        print("You are underweight")

    elif BMI <= 25:
        print("You are Healthy")

    elif BMI <= 30:
        print("You are overweight")

    else:
        print("You are severely overweight")

else:
    print("Please enter correct values")
