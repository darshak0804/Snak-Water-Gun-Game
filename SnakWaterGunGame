import random
lst = ["snak","water","gun"]



chance=10
no_of_chance=0
computer_point=0
human_point=0

print("\t\t\t Let's Start the Game\t\t\t")
print("Snak Water Gun")


while no_of_chance<chance:
    _input=input("snak,water,gun:")
    _random=random.choice(lst)

    if _input == _random:
        print("Both is Same that why is tie\n")

        # if user enter s
    if _input=="snak" or _random=="gun":
        computer_point=computer_point+1
        print(f"your guess is {_input} and computer guess is {_random}\n")
        print("computer wins 1 point")
        print(f"computer point is {computer_point} and your point is {human_point}\n ")

    elif _input=="snak" and _random=="water":
        human_point=human_point+1
        print(f"your guess is {_input} and computer guess is {_random}\n")
        print("you are the winner\n")
        print(f"computer point is {computer_point} and your point is {human_point}\n")

    elif _input=="gun" and _random=="snak":
        human_point=human_point+1
        print(f"your guess is {_input} and computer guess is {_random}\n")
        print("you are the winner\n")
        print(f"computer point is {computer_point} and your point is {human_point}\n")

    elif _input == "gun" and _random == "water":
        computer_point = computer_point + 1
        print(f"your guess is {_input} and computer guess is {_random}\n")
        print("computer is winner\n")
        print(f"computer point is {computer_point} and your point is {human_point}\n")

    elif _input == "water" and _random == "snak":
        computer_point = computer_point + 1
        print(f"your guess is {_input} and computer guess is {_random}\n")
        print("computer is winner\n")
        print(f"computer point is {computer_point} and your point is {human_point}\n")


    elif _input == "water" and _random == "gun":
        human_point = human_point + 1
        print(f"your guess is {_input} and computer guess is {_random}\n")
        print("you are the winner\n")
        print(f"computer point is {computer_point} and your point is {human_point}\n")

    else:
        print("you gave a wrong input please check for another time\n")

    no_of_chance=no_of_chance+1
    print(f"{no_of_chance} is left out of {chance}")

print("Game Over")

if computer_point > human_point:
    print("Computer wins and you loose")

elif computer_point < human_point:
    print("you win and computer loose")
else:
    print(f"your point is {human_point} and computer point is {computer_point}")
