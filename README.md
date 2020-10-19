# DMGuide
print("""
	
"Welcome great adventurer!
If you'd like to create a character
hit C and enter to begin making your fighter

""")


whle confirm_stats == True and roll_times <=3:
	if roll_times >= 1 and roll_times < 3:
		print(f" you have {4 - roll_times} roll_times left.")
	elif roll_times >= 3:
			print("This is your last chance to re roll. ")
			satisfied = input(f"Are you satisfied with your stats?
			"if you re-roll you cannot use a previous roll. Re-roll with r and move on with m >""")
	satisfied = input("are you satisfied with your stats? y/n ")
	if yes.lower() == 'y':
		confirm_stats = False
		
		
		
	else:
		[ Strength, agility, health] = Fighter()
		print(f"""
		"Strenght is: {strength}"
		"agility is: {agility}
		"health is: {health}
		"")
		roll_times += 1
		
		print("Your almost ready adventuer")
		char_name = input("Befor you begin on your Adventure what is your Adventuer's name? > '")
		print(f"{char_name} is ready to enter the dungeon!")
fighter1 = basicCharacter(char_name, strength, agility, health)
print(fighter1.char_stats())
		
while head_in:
	ready = input("Are you ready to head in? y/n")
	if ready.lower()	== 'y':
		DmGuide.room1.room_area()
