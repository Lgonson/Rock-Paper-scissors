# Rock-Paper-scissors
#Rock-Paper-scissors


#Hi! This is a Rock-Paper-Scissors game. 
#You have to choose an option and then let's play against the computer.
#I hope, you can have fun with this game. 


#The code is:

# Rock, Paper, Scissors Game:
import random
a = random.randint(1, 3)

if a == 1:
    computer = "Rock"
elif a == 2:
    computer = "Paper"
elif a == 3:
    computer = "Scissors"

user = input(f"Which option do you want to choose? Scissors, Rock or Paper?" )
user = user.upper()
if user == "SCISSORS":
    print(f"You have choosen {user}")
    if computer == "Scissors":
        print(f"The computer has also choosen {computer}.")
        print("So, it is a Draw")
    elif computer == "ROCK":
        print(f"The computer has choosen {computer}.")
        print("so, you Loose. :( ")
    else:
        print(f"The computer has choosen {computer}.")
        print("You're dammm goood. You're the winner of this season.")
elif user == "ROCK":
    print(f"You have choosen {user}")
    if computer == "Rock":
        print(f"The computer has also choosen {computer}.")
        print("So, it is a Draw")
    elif computer == "Paper":
        print(f"The computer has choosen {computer}.")
        print("so, you Loose. :( ")
    else:
        print(f"The computer has choosen {computer}.")
        print("You're dammm goood. You're the winner of this season.")
elif user == "PAPER":
    print(f"You have choosen {user}")
    if computer == "Paper":
        print(f"The computer has also choosen {computer}.")
        print("So, it is a Draw")
    elif computer == "Scissors":
        print(f"The computer has choosen {computer}.")
        print("so, you Loose. :( ")
    else:
        print(f"The computer has choosen {computer}.")
        print("You're dammm goood. You're the winner of this season.")
