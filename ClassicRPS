import random

rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''
game_images = [rock, paper, scissors]
print("Welcome to Rock Paper Scissors!")
user_choice = int(input("Type 0 for rock, 1 for paper and 2 for scissors.\n"))
computer_choice = random.randint(0,2)
if user_choice >= 0 and user_choice <= 2:
    print("You choose:")
    print(game_images[user_choice])

if user_choice > 2 :
    print(f"Computer choose {computer_choice}.")
    print("Its an Invalid Output")

elif user_choice == 0 and computer_choice == 2 :
    print(f"Computer choose:")
    print(game_images[computer_choice])
    print("You won the Game!")

elif computer_choice == user_choice :
    print(f"Computer choose:")
    print(game_images[computer_choice])
    print("Its a Draw!")


elif computer_choice == 0 and user_choice == 2:
    print(f"Computer choose:")
    print(game_images[computer_choice])
    print("You lost the game :(")


elif computer_choice > user_choice:
    print(f"Computer choose:")
    print(game_images[computer_choice])
    print("You lose :(")

elif computer_choice < user_choice:
    print(f"Computer choose :")
    print(game_images[computer_choice])
    print("You win!")
else :
    print("Invalid Input")
