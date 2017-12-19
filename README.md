# roll_dice_python
#A project for game of dice roll
from random import *

def roll():
    val=randint(1,6)
    return val
  
def main():
    flag=True
    
    while flag:
        ip=input("Press enter to roll and 'q' to quit \n")
        if ip.lower()!='q':
            op=roll()
            print("You got a",op)
        else:
            flag=False
            print("Thanks for playing,Bye!")
main()
