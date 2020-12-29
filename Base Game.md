# CodeRed                                          #
# First Classic Text Gaming Project       #
# Imports                                           #
import time

# Intro #
def IntoGame():
    print("CodeRed...")
    print("This is 3015, November")
    print("Im Maverickson a part time developer in the prestige Global Mixer Network or, GMN 2000.")
    Dialouge1()
# Choices Begin Here #
def Dialouge1():
    GMNQ1=input(" A: What is the GMN? \n B: What is a Gobal Mixer Network? \n C: Who am I? \n D: Whats Next? \n")
    if GMNQ1==("A"):
        print("Oh, The GMN is the Global Mixer Network. Used by many to create so many ideas to life")
        input("Press Enter....")
        knowGMN.append("GMN A")
        Dialouge1()
    if GMNQ1==("B"):
        print("Its a datacenter usable, configurable, and downloadable by any systematically connected source of life. \n It's like the old 2010 Virtual Reality Headset but... 1 x 10 -6 better.")
        input("Press Enter....")
        knowGMN.append("GMN B")
        Dialouge1()
    if GMNQ1==("C"):
        print("Depends, do you mean physically or mechanically? \n They're two different people technically.")
        input("Press Enter....")
        knowGMN.append("GMN C")
        Dialouge1()
    if GMNQ1==("D"):
        input("Press Enter....")
        TheWaking()
        
#  The Waking  #
def TheWaking():
    for i in range(80):
        print("             ")
    print(" So you dont look like you understand what life is nowa days do yah? \n Well umm it's 3015 like I said and its November so deals for nanotech are occuring. \n Lets get you some clothing I guess")
    print(" There's 3 main brands running the market as of today so which one do you wanna take a look at? \n ")
    brands=input(" A: Cyberwares   B: Night Cloak   C: Ether Lights  ")
    if brands==("A"):
        for i in range(80):
            print ("   ")
        print("CYBERWARES ----------- CYBERWARES CYBERWARES ----------- CYBERWARES CYBERWARES ----------- CYBERWARES")
        print("                                                                                                                                                                         ")
        print("                 Clothing made for the most elite fighters, bounty hunters, or your average street runner hacker                ")
        print("                                                                                                                                                                          ")
        print("                           Shirt                Jacket             Jean            Shoe              Accesories                                            ")
        print("      ___________________________________________________________________________________               ")
        print("                                                                                                                                                                          ")
        print("     175 PTUs--| Tight Fitted Shirt  ---  Black Leather Studded --- Tight Cyberthreads --- Elite Bouncer Shoes ---          ")
        print("     200 PTUs--| 80's Dress Shirt --- Armored Jacket --- Ripped Long Jeans --- Heavy Weight Training Shoes ---            ")
        clothchoice=input("Would you like this clothing brand?\n [Yes]\n [No]")
        if clothchoice == ("Yes"):
            Brands.append("Cyberwares")
            MentalSync()
        else:
            TheWaking()
        
    if brands==("B"):
        for i in range(80):
            print ("   ")
        print("NIGHT CLOAK ----------- NIGHT CLOAK | NIGHT CLOAK ----------- NIGHT CLOAK | NIGHT CLOAK ----------- NIGHT CLOAK")
        print("                                                                                                                                                                         ")
        print("                           Clothing made for the most rouge personas, thieves, or your shady GMN dealer                             ")
        print("                                                                                                                                                                          ")
        print("                           Shirt                Jacket             Jean            Shoe              Accesories                                            ")
        print("      ___________________________________________________________________________________               ")
        print("                                                                                                                                                                          ")
        print("     175 PTUs--| Pocketed Black Tech  --- Screen Intercepting Cloak --- Pocketed Sweats --- Smooth Slider Shoes ---    ")
        print("     200 PTUs--| White Plated Shirt --- Fancy Blue Jeans --- Trace Reducing Boots ---                                                 ")
        clothchoice=input("Would you like this clothing brand?\n [Yes]\n [No]")
        if clothchoice == ("Yes"):
            Brands.append("NightCloak")
            MentalSync()
        else:
            TheWaking()

        
    if brands==("C"):
        for i in range(80):
            print ("   ")
        print("ETHER LIGHTS ----------- ETHER LIGHTS | ETHER LIGHTS ----------- ETHER LIGHTS | ETHER LIGHTS ----------- ETHER LIGHTS")
        print("                                                                                                                                                                          ")
        print("                           Clothing made for the most flashy personas, celeberities, or The Wanna Be's                                  ")
        print("                                                                                                                                                                          ")
        print("                           Shirt                Jacket             Jean            Shoe              Accesories                                            ")
        print("      ___________________________________________________________________________________               ")
        print("                                                                                                                                                                          ")
        print("     175 PTUs--| Etherum Threaded Dress Shirt  --- Classic Over Coat --- Dress Jeans --- Hover Etherum Powered Slides --- ")
        print("     200 PTUs--| White Etherum Laced Dancer Shirt --- Fancy White Jeans --- Gold Rimmed Shoes --- Flashy Gold Chain --- ")
        clothchoice=input("Would you like this clothing brand?\n [Yes]\n [No]")
        if clothchoice == ("Yes"):
            Brands.append("EtherLights")
            MentalSync()
        else:
            TheWaking()

# Mental Sync #
def MentalSync():
    for i in range(80):
        print("    ")
    print(" . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . . ")
    print("  . . . . . .  Mental  . . . . . .  . . . . . .  Sync  . . . . . .  . . . . . .  Proccess . . . . . .  . . . . . .  Continuing  . . . . . .")
    print(" . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . .  . . . . . . ")
    time.sleep(10)
    for i in range(80):
        print("   ")
    print("Sync Mental Complete")
    print("Launching Mental World")
    time.sleep(5)
    for i in range(80):
        print("   ")
    print(". ")
    time.sleep(3)
    for i in range(80):
        print("   ")
    print(". .")
    time.sleep(3)
    for i in range(80):
        print("   ")
    print(". . . ")
    time.sleep(3)
    for i in range(80):
        print("   ")
    print(". . . .")
    time.sleep(3)
    for i in range(80):
        print("   ")
    print("Succesful Boot")
    time.sleep(2)
    World1()

# World 1 ---- Helgar ---- #
def World1():
    print(" The skimming skies of Helgar feel your breath and your lungs. \n You step toe to a new in which cells of your physical body take on currency. \n Your first life may be right here or waiting for you in a dark corner of a bar... \n")
    



    

#Knowledge Tables#
knowGMN = []
Brands = []
#PTUs Scale#
PTU = 500
IntoGame()
