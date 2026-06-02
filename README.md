# number_guessing_game

secret = 7

guess = int(input("Guess a number between 1 and 10: "))

if guess == secret:
    print("You win!")
else:
    print("Wrong guess!")
