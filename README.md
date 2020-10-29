# Random-Number-Game
def randomnumbergame():

 import random

 number = random.randint(0, 100)

 name = input("Enter your name:")

 print("Hello, ",name,"!")
 print ("lets play a game, guess a number 0 to 100")
 
 loop = True
 while loop: #continue forever....
   guess = int(input("enter your guess: "))
   if guess > number:
    print (" You are to high ")
   elif guess < number:
     print (" You are too low " )
   else:
    print ( " You win, " )
    loop = False
     
     
randomnumbergame()
