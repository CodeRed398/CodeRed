# CodeRed                                           #
# First Classic Text Gaming Project                 #
# Imports                                           #
import time



# Screen Tools #
def ClearLED():
    for i in range(90):
        print("         ")



# Intro
def IntoGame():
    print("CodeRed...")
    print("This is 3015, November")
    print("Im Maverickson a part time developer in the prestige Global Mixer Network or, GMN 2000.")
    Dialouge1()




# Choices Begin Here
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
    else:
        Dialouge1()
        
        
        
        
        
#  The Waking
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
        clothchoice=input("Would you like this clothing brand?\n [Yes]\n [No]\n   ")
        if clothchoice == ("Yes"):
            Brands.append("EtherLights")
            MentalSync()
        else:
            TheWaking()
        
            
            
            
            
            
            
# Mental Sync 
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
    print(" The skimming skies of Helgar feel your breath and your lungs. \n You step toe to a new world in which cells of your physical body take on currency. \n Your first life may be right here or waiting for you in a dark corner of a bar... \n")
    time.sleep(5)
    ClearLED()
    Apartment273()
    
    
    
    
# World 1 ---- Apartment 273 #
def Apartment273():
    print("The steel handlebars of almost captitude hold you prison to your now new building of life. \n You feel a tingle strife in your blood stream and your fingers click mechanically to the metal tapping softly.\n A TV buzzes static and fills your brain with only the sound. ")
    print("Cars pass below and people yell and fight. \n Gun shots in the distant tell you this new world is not the safest of an area and a bright LED screen blazes through the night \n showing loud advertisments for NERU enhancements.")
    EyeDis=input("Choose what to do... \n \n \n Actions: \n Jump \n Turn TV \n Study Streets \n Leave Apartment :   ")
    if EyeDis==("Jump"):
        ClearLED()
        print("Wow your a retard huh? okay! I mean I did give you a choice")
        exit
    if EyeDis==("Turn TV"):
        ClearLED()
        print("You switch to a clear station on NERU enhancers. \n The quality is low and static stills seeps into the channel...")
        Cultural.append("Neru enhancers")
        time.sleep(5)
        ClearLED()
        Apartment273()
    if EyeDis==("Study Streets"):
        print("The hustles of busy feet and the roar of car engines bursts through the small city and seem to blaze away as fast as they come.")
        time.sleep(5)
        ClearLED()
        print("You see a couple of beast looking men rustle into the alleyway violently and yelling, a loud shot is fired then silence for a second")
        print("...")
        print("......")
        Cultural.append("Beast Fight")
        time.sleep(5)
        ClearLED()
        Apartment273()
    if EyeDis==("Leave Apartment"):
        ClearLED()
        print("Your open the door and its quick, the smell of dust and alcohol surround your face.")
        print("A door is open and a small boy sits outside it as you hear yelling from the door.")
        print("He's head down in his knees clearly hating his own life as well.")
        time.sleep(10)
        ClearLED()
        if "Hall Boy" in People:
            Hallway()
        else:
            HallwayNoBoy()
    else:
        Apartment273()





# HALLWAY Interaction 
def Hallway():
    Relations=input("What are you to do huh? \n Actions: \n Walk Past \n Kick Him \n Talk \n Go Back :   ")
    if Relations==("Kick Him"):
        ClearLED()
        print("A man steps out eyes furious with rage and he grips your throat tight. \n You lungs grasp to a finale breathe before darkness")
        time.sleep(10)
        ClearLED()
        print(".")
        time.sleep(2)
        print("..")
        time.sleep(3)
        print("...")
        time.sleep(3)
        print("........................................... PRINTING RECEIPT ........................................")
        time.sleep(5)
        print("........................................... REBOOTING ...... SUCCESS.................................")
        time.sleep(5)
        quit()
    if Relations==("Talk"):
        ClearLED()
        print("He looks up as your mouth moves and you notice his mouth is displaced. \n Not odd, just gone with no cuts or rips.")
        time.sleep(3)
        ClearLED()
        print("Your eye atones to the image and his eyes adjust. \n Your seeing the effects of dangerously rejected neru-enhancer failures. \n Its not pretty...")
        NeruK.append("Neru Failure")
        time.sleep(5)
        ClearLED()
        Help=input("You gonna leave him there? \n Actions: \n Put Him Out Of His Misery \n Walk Away :   ")
        if Help==("Put Him Out Of His Misery"):
            time.sleep(5)
            ClearLED()
            print("You look for anything to 'Help' him, you cant see more than a knife busted and crooked. You grip it")
            time.sleep(2)
            ClearLED()
            print("..........OPTICIS BOOTING.........")
            time.sleep(3)
            ClearLED()
            print(".........OPTIC BOOT SUCCESS.......")
            time.sleep(5)
            ClearLED()
            print("The knife rest deepened into the skull of the boy and blood spurts out. \n Your hands pulse with rythme and your fingers settle.")
            People.remove("Hall Boy")
            time.sleep(5)
            ClearLED()
            HallwayNoBoy()
        if Help==("Walk Away"):
            print("You walk past and the hallway leaves you as you leave it.")
            print("A staircase door presents to you and the creak of wind breaks the silence you feel.")
            Stairs()
        else:
           Hallway()
    if Relations==("Go Back"):
        ClearLED()
        Apartment273()    
    else:
        ClearLED()
        Hallway()
        
# If You Kill The Boy #
def HallwayNoBoy():
    RelationsN=input("What are you to do huh? \n Actions: \n Walk \n Go Back \n \n :  ")
    if RelationsN==("Walk"):
        print("You walk past and the hallway leaves you as you leave it.")
        print("A staircase door presents to you and the creak of wind breaks the silence you feel.")
        Stairs()
    if RelationsN==("Go Back"):
        ClearLED()
        Apartment273()
    else:
        HallwayNoBoy()



# Stairwell #
def Stairs():
    ClearLED()
    print("Its silence still. \n The stairs are wood, somehow holding up.")
    print("You walk your way down the set of stairs and find another door.")
    time.sleep(5)
    ClearLED()
    print("A sign next to the door states exit. \n You push the door and a bright gleeming light of the sun hits you.")
    print("A few people bustle back and forth around this small alleyway exit...")
    time.sleep(3)
    AWay=input("Actions: \n Walk Right \n Walk Left \n Prop Against The Wall :   "):
        if AWay==("Walk Right")
            ClearLED()
            time.sleep(2)
            print("You take a right and meet a alley of Vending Machines and food")
            time.sleep(5)
            VM=input("Take A Look? Actions: \n Yes \n No :   "):
                if VM==("Yes")
                    ClearLED()
                    VendingMachines()
                if VM==("No")
                    ClearLED()
                    Stairs()
        if AWay==("Walk Left")
            ClearLED()
            print("The Pavemnet road meets your feet and you rushes of people crowd as they pass you.")
            print("Cars drive past some blazing by and some slowly scooting by. \n Those same cars contain people peering out the windows and looking for something")
            time.sleep(8)
            Streets()
        if AWay==("Prop Against The Wall")
            ClearLED()
            print("Your back props up and time passes by \n people as well.")
            time.sleep(3)
            ClearLED()
            print("11 am - - -")
            time.sleep(3)
            ClearLED()
            print("2 pm - - -")
            time.sleep(3)
            ClearLED()
            print("4pm - - -")
            time.sleep(3)
            ClearLED()
            print("7pm - - -")
            time.sleep(5)
            print("Your body enter neru statis...")
            NeruK.append("Neru_stasis")
            time.sleep(5)
            ClearLED()
            
        else:
            ClearLED()
            Stairs()
def Streets():
    Streets1=input("Actions: \n ")
def VendingMachines():
    print("They line you up and list items of all sorts.")
    print("Sodas, Neruenhancer Sprays, Mechanical Part, and Small Foods and Snacks")
    VendCH=input("Actions: \n Buy Soda \n Buy Neru-enhancer Spray \n Buy Mechanical Part \n Buy Food \n Back :   "):
        if VendCH==("Buy Soda"):
            ClearLED()
            print(" ...       Soda Receipt          ... ")
            print("                                     ")
            print(" ...        PTUS -- 25           ... ")
            PTU = PTU - 25
            print(" ... Remaining Balance " PTU "'s ... ")
            print("                                     ")
            print(" ...       Soda Receipt          ... ")
            Food.append("Soda")
            time.sleep(3)
            ClearLED()
            VendingMachines()
        if VendCH==("Buy Neru-enhancer Spray"):
            ClearLED()
            print(" ... Neru-enhancer Spray Reciept ... ")
            print("                                     ")
            print(" ...        PTUS -- 175          ... ")
            PTU = PTU - 175
            print(" ... Remaining Balance " PTU "'s ... ")
            print("                                     ")
            print(" ... Neru-enhancer Spray Reciept ... ")
            Esc.append("Neur-Enhancer Spray")
            time.sleep(3)
            ClearLED()
            VendingMachines()
            


# Knowledge Tables | Knowledge Tables | Knowledge Tables #

#GMN is the Global Mixer Network#
knowGMN = []

#Brands as in clothing knowledge#
Brands = []

#Apartment and Helgar#
Cultural = []

#People#
People = ["Hall Boy"]

#Neru-enchancers#
NeruK = []

#CURRENCY#
# PTUs Scale, PTUs is in game currency#
PTU = 500

# Inventory #
Food = []
Esc = []
Weapons = []
Clothes = []
Accesories = []
Quest_Items = []

# Game Beginner #
IntoGame()
