# Python-Basic-To-Advance-Codes
GET HELP AND GIVE HELP...THANK YOU!!!
<<<<<<<<<<<<<<<<<<<<< METHODE 1 >>>>>>>>>>>>>>>>>>>>>>>>>>>>>

Character= input("Please Enter the WORD:")

if Character.isupper():
    print("The Given WORD", Character, "is an Uppercase.")
elif Character.islower():
    print("The Given WORD ", Character, "is a Lowercase.")
else:
    print("The Given WORD ", Character, "is Not a LowerCase nor LowerCase.")
    
 
 
 <<<<<<<<<<<<<<<<<<<<< METHODE 2 >>>>>>>>>>>>>>>>>>>>>>>>>>>

Character=input("Please Enter the Word:")

if (Character>="a" or Character<="z"):
          print("The Given WORD", Character, "is an LowerCase.")
elif (Character>="A" or Character<="Z"):
    print("The Given WORD ", Character, "is a UpperCase.")
else:
    print("The Given WORD ", Character, "is Not a UpperCase nor LowerCase.")
    
<<<<<<<<<<<<<<<<<<<<<METHODE 3 >>>>>>>>>>>>>>>>>>>>>>>>>>>
#ONLY FOR SINGLE INPUT>>

character = input("Please Enter Your Own Character : ")

if ord(character) >= 65 and ord(character) <= 90: 
    print("The Given Character ", ch, "is an Uppercase Alphabet") 
elif ord(character) >= 97 and ord(character) <= 122:
    print("The Given Character ", ch, "is a Lowercase Alphabet")
else:
    print("The Given Character ", ch, "is Not a Lower or Uppercase Alphabet")
