
import random as rand
tal = rand.randint(1, 10)
gissning = 0
while gissning != tal:
    try:
        gissning = int(input("Gissa ett tal mellan 1 och 10 -> "))
        if gissning < tal:
            print("Din gissning är för liten")
        elif gissning > tal:
            print("Din gissning är för stor")
        elif gissning == tal:
            print("RÄTT GISSAT!")
    except ValueError:
        print("Ange ett heltal mellan 1 och 10")

              
