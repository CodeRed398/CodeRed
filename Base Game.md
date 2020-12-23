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
        print("                                                                                                                                                                          ")
        
        
    if brands==("B"):
        end
    if brands==("C"):
        end




#Knowledge Tables#
knowGMN = []
knowClothing = []
IntoGame()
