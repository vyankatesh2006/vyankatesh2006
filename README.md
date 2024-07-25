print("WELCOME TO ROCK SEACOR GAME")
usear_choice = int(input("\n what do you choice: Type 0 for rock , 1 for seacor and 2 for Paper "))
computer_choice = random.randint(0,2)
print(f"computer choice {computer_choice}")

if usear_choice == 0 and computer_choice == 2:
  print("you win")
elif computer_choice > 3 or usear_choice < 0:
  print("you type invalid number")
elif usear_choice == computer_choice:
  print("it is draw")
elif usear_choice == 1 and computer_choice == 0:
  print("you win")
elif usear_choice == 2 and computer_choice == 1:
  print("you win")
elif usear_choice == computer_choice:
  print("it is draw")
else:
  print("you lose")

  
