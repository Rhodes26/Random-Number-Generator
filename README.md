# Random-Number-Generator.
import random
print("Welcome to the random number game")
num = random.randint(1,10)
guess = None
while guess != num:
     guess = input("guess a number between 1 and 10: ")
     guess = int(guess)
     if guess == num:
        print("Congrats! You guessed the number")
        break
     else:
        print("Sorry, wrong number. Try again.")
