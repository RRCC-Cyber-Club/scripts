def fav_color():
	a = input("What is your favorite color?")
	if color == "Red":
		print("That's my favorite color too!")
	else:
		print(f"{a} is also a good color")
	while True:
		go_again=input("Would you like to go again")
		if go_again == 'y' or go_again == 'Y':
			