# game2
#A Game of guessing the correct number
import random
com=random.randint(1,100)
l=0
you=-1
print("guess the number from 1 to 100\n")

while(you!=com):
    you=int(input("guess the number :   "))
    if (you>com):
        print("LOWER value please\n")
    elif(you<com):
        print("HIGHER value please\n")
    l=l+1
print("")
print("")
print(f"CONGRATS you guessed it right in {l} attempts!!!\nthe number was {com}")
print("")
