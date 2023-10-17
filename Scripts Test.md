
'''
Fav Color Game
Coded by Antonio
'''
def fav_color():
	color = input("What is your favorite color?")
	if color == "Red" or color == 'red':
		print("That's my favorite color too!")
	else:
		print(f"{color} is also a good color")
	while True:
		go_again = input("Would you like to go again? y/N\")
		if go_again == 'y' or go_again == 'Y':
			fav_color()
		elif go_again == 'n' or go_again == 'N':
			print("Goodbye")
			break
fav_color()