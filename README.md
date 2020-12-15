# Password_guesser

import random

def guesser():
	passwdlst= [input("Enter a list of passwords")]
	
	todays_password= random.choice(passwdlst)
	print(todays_password)


