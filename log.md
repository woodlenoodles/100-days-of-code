# 100 Days Of Code - Log

### Day 1: February 3rd 2022

**Today's Progress**: Learned print(), input() functions and variable naming.

**Thoughts:** Struggled when trying to get 2 variables to spit out each other's values. c = a, a = b, b = c. But there is a way to do that with only 2 variables!

**Link to work:** https://replit.com/@AndrewWu21/tip-calculator-start

### Day 2: February 4th 2022

**Today's Progress**: Data type manipulation. PEMDAS. Built BMI calculator and tip calculator. Formatting decimal points = "{:.2f}".format(variable)

**Thoughts** How do you write piped code?

**Link(s) to work**: https://replit.com/@AndrewWu21/day-3-start

### Day 3: February 4th 2022

**Today's Progress**: Nested if/else/elif statements. Indentations matter! New functions: lower() e.g variable.lower() and the count() e.g variable.count(x)

**Thoughts** KINDA HARD.

**Link(s) to work**: https://replit.com/@AndrewWu21/treasure-island-start

### Day 4: February 5th 2022

**Today's Progress**: Random modules and lists. Nested lists are annoying (treasure map). Built a rock paper scissors using random module (import random, random.randint(range))

**Thoughts** Not too bad!

**Link(s) to work**: https://replit.com/@AndrewWu21/rock-paper-scissors-start

### Day 5: February 5th 2022

**Today's Progress**: Working with loops and range in loops. New functions = random.choice(list) and random.shuffle(list). Range = how many cycles to go through the list. 

for x in list:
  variable > item in list
  variable = item in list
(Makes variable the item in the list until it reaches the highest item)

**Thoughts** Really tough at hard parts.

**Link(s) to work**: https://replit.com/@AndrewWu21/password-generator-start

### Day 6: February 6th 2022

**Today's Progress**: Working with while loops, indentations and defining own functions.

**Thoughts** Need to get better at thinking logically and not taking the long way around solutions. Exiting the maze was really hard :(

**Link(s) to work**: https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=problem_world2.json&url=user_world%3Aproblem_world2.json

### Day 7: February 7th 2022

**Today's Progress**: Built hangman. variable in/not in lists/string. 

display = [ ]
len_word = len(chosen_word)
for i in range(len_word):
  display += "_"
# print(display)

guess = input("Guess a letter: ").lower()

for position in range(len_word): 		Range determines how many cycles the for loop runs.
								Position starts at “0”
  letter = chosen_word[position]		“0” position inserted into chosen_word and associates it with the first letter
								If guess = the letter: “_” position in list is replaced by guess
								If guess != letter: returns to the for loop and runs the next cycle
  if letter == guess:
    display[position] = guess
print(display)

Kramm said use FLAGS! Boolean = TRUE/FALSE

**Thoughts** WE DID IT BOIZ.

**Link(s) to work**: https://replit.com/@AndrewWu21/Day-7-Hangman-5-Start#main.py

### Day 8: February 8th 2022

**Today's Progress**: Function parameters. Defining functions. Built caesar encryption. Prime number checker.

**Thoughts** KINDA HARD.

**Link(s) to work**: https://replit.com/@AndrewWu21/caesar-cipher-4-start#main.py

### Day 9: February 9th 2022

**Today's Progress**: Dictionaries and nests. dictionary = {}. Can be in a list or can include a list.

**Thoughts** KINDA HARD.

**Link(s) to work**: https://replit.com/@AndrewWu21/blind-auction-start-1#main.py

Day 10: February 12th 2022
Today's Progress: Made a calculator using dictionaries, while loops and recursion. Recursion = calling function within its definition but must be associated with conditions!

Thoughts KINDA HARD.

Link(s) to work: https://replit.com/@AndrewWu21/calculator-start#main.py

Day 11: February 12th 2022
Today's Progress: Made a working Blackjack game for my first Capstone project!

Thoughts KINDA HARD.

Link(s) to work: https://replit.com/@AndrewWu21/blackjack-start#main.py

Day 12: February 12th 2022
Today's Progress: Made a number guessing game. More refined than Blackjack and felt a lot easier to do!

Thoughts KINDA HARD.

Link(s) to work: https://replit.com/@AndrewWu21/guess-the-number-start#main.py

Day 13: February 13th 2022
Today's Progress: Debugged code.

Thoughts Meh.

Link(s) to work: No projects.

Day 14: February 13th 2022
Today's Progress: Built Higher/Lower game.

Thoughts Didn't seem so bad! Always a good idea to define functions instead of repeating code.

Link(s) to work: https://replit.com/@AndrewWu21/higher-lower-start#main.py

Day 15: February 15th 2022
Today's Progress: Built a coffee machine using PyCharm

Thoughts Didn't seem so bad! Always a good idea to define functions instead of repeating code <- did this this time!

Link(s) to work: PyCharm file.

Day 16: February 18th 2022
Today's Progress: Built a coffee machine using PyCharm and OOP!

Thoughts Calling classes must be outside of loops otherwise they keep resetting!!!

Link(s) to work: PyCharm file.

Day 17: February 20th 2022
Today's Progress: Creating classes, attributes and methods using OOP and using them for modular code.

Thoughts Needs work.

Link(s) to work: PyCharm file.

Day 18: February 20th 2022
Today's Progress: Turtle classes, colorgram and generating the Hirst Painting Project

Thoughts: My solution was better lmao.

Link(s) to work: PyCharm file.

