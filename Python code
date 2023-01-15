import random

durchgang = 0
aktiv = True
ratezahl = random.randint(0, 100)

while aktiv:
    durchgang = durchgang + 1
    print()  # für Abstand (nur Optik)
    print(durchgang)
    benutzereingabe = int(input("Type in your number: "))

    if benutzereingabe == ratezahl:
        print("You win! The secret number has now been revealed")
        aktiv = False
        break
    elif benutzereingabe > ratezahl:
        print("this number is way too big")
    else:
        print("this number is too small")

    if (durchgang == 7):
        print("Game Over! Try again!")
        print("Es war die Zahl " + str(ratezahl))
        aktiv = False
print("End of the game")
