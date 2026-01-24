# I-monlyforuNish-Pu
# For the remainder for my crus*
import time
import random
import os
import sys

name = "N I S H A"
chars = "01@#$%&*ABCDEFGHIJKLMNOPQRSTUVWXYZ"

def clear():
    os.system("clear")
    
clear()
for c in "Initializing system...\n":
    sys.stdout.write(c)
    sys.stdout.flush()
    time.sleep(0.05)

time.sleep(1)

for _ in range(10):
    clear()
    for i in range(10):
        line = "".join(random.choice(chars) for _ in range(60))
        print(line)
    time.sleep(0.1)

clear()
while True:
    clear()
    for i in range(10):
        print(" " * random.randint(0, 30) + name)
        time.sleep(0.1)

    print("\n")
    for letter in "NISHA":
        sys.stdout.write(letter + " ")
        sys.stdout.flush()
        time.sleep(0.5)

    time.sleep(1)
