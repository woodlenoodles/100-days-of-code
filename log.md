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

Day 19: February 21th 2022
Today's Progress: Programming the turtle race

Thoughts: My solution was better lmao.

Link(s) to work: PyCharm file.

Day 20: February 21th 2022
Today's Progress: Building and animating the snake game. Need work on creating class and OOP. init function is for everything to start up the class when called.

class Snake:

    def __init__(self):
        self.segments = []
        self.create_snake()
        self.head = self.segments[0]

    def create_snake(self):
        x_pos = 0
        for i in range(3):
            snake = Turtle()
            snake.penup()
            snake.shape("square")
            snake.color("white")
            x_pos -= 20
            snake.setpos(x_pos, 0)
            self.segments.append(snake)

    def move_snake(self):
        for segment in range(len(self.segments) - 1, 0, -1):
            new_x = self.segments[segment - 1].xcor()
            new_y = self.segments[segment - 1].ycor()
            self.segments[segment].setpos(new_x, new_y)
        self.segments[0].forward(20)

Thoughts: My solution was better lmao.

Link(s) to work: PyCharm file.

Day 21: February 24th 2022

Today's Progress: Snake Game Pt. 2. Class inheritance and slice lists

Thoughts: My solution was better lmao.

Link(s) to work: PyCharm file.

Day 22: February 24th 2022

Today's Progress: Pong Game - OOP practice.

Thoughts: My solution was better lmao.

Link(s) to work: PyCharm file.

Day 23: March 4th 2022

Today's Progress: Turtle Crossing Game - More OOP Practice


class CarManager:
    def __init__(self):
        self.all_cars = []
        self.car_speed = STARTING_MOVE_DISTANCE

    def create_cars(self):
        random_chance = random.randint(1, 6)
        if random_chance == 1:
            new_car = Turtle("square")
            new_car.shapesize(stretch_len=2)
            new_car.color(random.choice(COLORS))
            new_car.penup()
            random_ycor = random.randint(-250, 250)
            new_car.setpos(300, random_ycor)
            self.all_cars.append(new_car)

    def move_cars(self):
        for car in self.all_cars:
            car.setheading(180)
            car.forward(self.car_speed)

    def speed_up(self):
        self.car_speed += MOVE_INCREMENT
	
import time
from turtle import Screen
from player import Player
from car_manager import CarManager
from scoreboard import Scoreboard

screen = Screen()
screen.setup(width=600, height=600)
screen.tracer(0)
screen.listen()

player = Player()
cars = CarManager()
scoreboard = Scoreboard()
screen.onkey(player.move, "Up")


game_is_on = True
while game_is_on:
    time.sleep(0.1)
    screen.update()

    cars.create_cars()
    cars.move_cars()
    scoreboard.update_scoreboard()

    for car in cars.all_cars:
        if car.distance(player) < 20:
            game_is_on = False
            scoreboard.game_over()

    if player.ycor() == 280:
        player.go_home()
        cars.speed_up()
        scoreboard.level_up()

Thoughts: My solution was better lmao.

Link(s) to work: PyCharm file.

Day 24: March 4th 2022

Today's Progress: Files, Directories, Paths

Thoughts: 

# Return all names as a list
wd = "/Users/andrewwu/OneDrive/PyCham Projects/Mail Merge Project Start"
with open(wd + "/Input/Names/invited_names.txt") as invited_names:
    name_list = invited_names.readlines()

# Replace [name] in Input/Letters/"starting_letter.txt"
for name in name_list:
    stripped_name = name.strip('\n')
    with open(wd + "/Input/Letters/starting_letter.txt") as starting_letter:
        search_text = "[name]"
        data = starting_letter.read()
        data = data.replace(search_text, stripped_name)

    with open(wd + f"/Output/ReadyToSend/{name}_letter.txt", mode = "w") as starting_letter:
        starting_letter.write(data)
	
Link(s) to work: PyCharm file.

Day 25: March 7th 2022

Today's Progress: Files, Directories, Paths. Panda Read CSVs

Thoughts: 

import turtle
import pandas
import pandas as pd

screen = turtle.Screen()
screen.title("U.S. States Game")
image = "blank_states_img.gif"
screen.addshape(image)

turtle.shape(image)

data = pandas.read_csv("50_states.csv")
list_states = data.state.to_list()


correct_guesses = []


def print_state(x, y):
    name = turtle.Turtle()
    name.ht()
    screen.tracer(1)
    name.penup()
    name.color("black")
    name.setpos(x, y)
    name.write(answer_state, align = "center", font = ("Arial", 12, "normal"))


game_on = True
score = 0
while game_on:
    answer_state = screen.textinput(title=f"{len(correct_guesses)}/50", prompt="What's another State's name?").title()
    if answer_state.title() in list_states:
        match = data[data.state == answer_state.title()]
        print_state(int(match.x), int(match.y))
        correct_guesses.append(answer_state.title())
        score += 1
        if len(correct_guesses) == 50:
            game_on = False
    elif answer_state == "done":
        game_on = False
        print(f"Your final score is: {score}")
        states_to_learn = []
        for states in list_states:
            if states not in correct_guesses:
                states_to_learn.append(states)
        states_to_learn_df = pd.DataFrame(states_to_learn, columns=["States"])
        states_to_learn_df.to_csv("states_to_learn.csv")






screen.exitonclick()



Link(s) to work: PyCharm file.

