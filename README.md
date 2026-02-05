# Error Prone Assignment
There are 17 Bugs across both files:
14 in error_code.py
3 in error_code_functions.py
-------------------------
Fixed errors in main:
Line 5: error_code_function --> error_code_functions
Line 5: createMonster --> create_monster
Line 90: "name" --> 'name'
Line 107: Luck --> luck
Line 10: items = [] -->             
Line 42: and --> or
Line 100: --> char_class = char_class["gold"] + gold --> char_class["gold"] += gold
Line 46: TypeError --> ValueError
Line 44+45: --> char_class = int(input("Please pick a character class:\n1. Fighter\n2. Wizard\n3. Rogue\n"))
Line 79: (monster, character class) --> (char_class, monster)
Line _
Line _
Line _
Line _
--------------------------
Fixed errors in functions:
Line 9, 14: - --> -=
Line _
Line _