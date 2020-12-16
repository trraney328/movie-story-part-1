import os
from os import system
import time
from time import sleep
import sys

black = "\033[0;30m"
purple = "\033[0;35m"
blue = "\033[0;34m"
green = "\033[0;32m"
red = "\033[0;31m"
yellow = "\033[0;33m"
white = "\033[0;37m"
cyan ="\033[0;36m"

def scrollTxt(text):
   for char in text:
        sys.stdout.write(char)
        sys.stdout.flush()
        sleep(0.07)

print(white)

scrollTxt("previously on movie story, \n")
scrollTxt('Programmer100: we need to shoot the rocket up in the sky \n')

time.sleep(3)
system('clear')

scrollTxt("And Now for the New Movie Story Part 1: \n")

time.sleep(3)
system('clear')

scrollTxt('Travis: \n')
scrollTxt('Oh Man, Where am I? \n')
time.sleep(1)
print(cyan)
scrollTxt('Tsunami:')
print(white)
scrollTxt('Dude, I saved you from the Killer! \n')
time.sleep(1)
print(yellow)
scrollTxt('BobTheCarrotCake:')
print(white)
scrollTxt('Yo, I noticed what happened to you \n')
time.sleep(1)
print(white)
scrollTxt('Travis: \n')
scrollTxt('Well, where is my son?\n')
time.sleep(1)
print(cyan)
scrollTxt('Tsunami:')
print(white)
scrollTxt('Well, we dont know exactly where your son is at, but we know that the earth is going to get blown up if we dont do something about it! \n \n')
time.sleep(1)
scrollTxt('Travis: \n')
scrollTxt('Well, guess what, there is a rocket not far from here, lets go!\n')
time.sleep(3)
system('clear')
scrollTxt('Meanwhile... at the rocket station \n \n')
scrollTxt('Travis: \n')
scrollTxt('Come on, hurry up and get in your space suits! \n')
time.sleep(1)
print(cyan)
scrollTxt('Tsunami: ')
print(white)
scrollTxt('Yes, boss. Right away, boss. \n')
time.sleep(1)
print(yellow)
scrollTxt('BobTheCarrotCake:')
print(white)
scrollTxt('yes, sir boss \n \n')
time.sleep(1)
scrollTxt('Travis: \n')
scrollTxt('Lets get in this rocket and go to the moon, because I believe that is where my son is at. \n')
time.sleep(3)
system('clear')

scrollTxt('Later... \n \n')
time.sleep(1)

scrollTxt('Travis:\n')
scrollTxt('I see My son!!!\n')
print(cyan)
scrollTxt('Tsunami:')
print(white)
scrollTxt('Someone is right beside your son, its Programmer100!!\n \n')
time.sleep(1)
scrollTxt('Travis: \n')
scrollTxt('where have you been?\n')
scrollTxt('Programmer100: \n')
scrollTxt('the bomb was ticking and now the whole earth is going to explode!\n \n')
time.sleep(1)
scrollTxt('Travis:\n')
scrollTxt('Nooooooooo, I failed to stop the killer!\n \n')
time.sleep(1)
scrollTxt('TO BE CONTINUED.....\n')
