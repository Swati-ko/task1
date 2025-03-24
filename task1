import random

def guess_the_number():
    # Generate a random number between 1 and 100
    random_number = random.randint(1, 100)
    print("Welcome to 'Guess the Number'!")
    print("I've picked a number between 1 and 100. Try to guess it!")

    while True:
        try:
            # Get the user's guess
            guess = int(input("Enter your guess: "))
            
            # Provide feedback
            if guess < random_number:
                print("Too low! Try again.")
            elif guess > random_number:
                print("Too high! Try again.")
            else:
                print(f"Congratulations! You guessed it right. The number was {random_number}.")
                break
        except ValueError:
            print("Please enter a valid number.")

# Run the game
guess_the_number()
