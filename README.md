# A-die-Game-
It's my First Coding 
import random 

print("Welcome to the Die Simulator!")
while True:
    choice = input("Press 'Enter' to roll the die or 'q' to quit")
    choice = choice.strip()
    if choice == "q":
        print("Thanks for Playing")
        break
    elif choice == "":
        number = random.randint(1,6)
        print(f"Your number is {number}")
    else:
        print("Invalid input. Try again.")

print("Game Over!")
