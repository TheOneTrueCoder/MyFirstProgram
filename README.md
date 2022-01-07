# MyFirstProgram
My First Fully Coded Program


import random

roll = input("Would you like to roll, yes or no? ")


while roll.lower() == "yes":
    print(random.randint(1, 6))
    roll = input("Would you like to roll again? ")

while roll.lower() != "yes" and roll.lower() != "no":
    roll = input("Please answer yes or no: ")
    while roll.lower() == "yes":
        print(random.randint(1, 6))
        roll = input("Would you like to roll again? ")

if roll.lower() == "no":
    print("Have a good day") 
