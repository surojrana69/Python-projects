import random

def number_guessing_game():
    number_to_guess = random.randint(1, 20)
    attempts = 0

    while True:
        guess = int(input("Guess the random number between 1 and 20: "))
        attempts += 1

        if guess < number_to_guess:
            print("Your guess is too low")
        elif guess > number_to_guess:
            print("Your guess is too high")
        else:
            print(f"Nice work! You have guessed the number correctly in {attempts} attempts.")
            break

number_guessing_game()
