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

Day 26: March 8th 2022

Today's Progress: List/Dictionary Comprehension

Thoughts: 

# #TODO 1. Create a dictionary in this format:
# {"A": "Alfa", "B": "Bravo"}

nato_dict = {row.letter:row.code for (index, row) in nato_data.iterrows()}


# #TODO 2. Create a list of the phonetic code words from a word that the user inputs.

user_input = input("Enter a word: ").upper()
output = [nato_dict[letter] for letter in user_input]
print(output)

Link(s) to work: PyCharm file.

Day 27: March 8th 2022

Today's Progress: *args, **kwargs, GUI using tkinter

Thoughts: 

NOT TOO BAD!

import tkinter
from tkinter import *

window = tkinter.Tk()

window.minsize(width = 400, height = 100)

window.title("Mile to Km Converter")

window.config(padx = 40, pady = 40)

def calculate():
    user_input = entry.get()
    answer = float(user_input) * 1.609344
    result.config(text = answer)

# Label
miles = Label(text="Miles", font = ("Arial", 20))
miles.config(padx = 10, pady = 10)
miles.grid(column = 3, row = 0)

is_equal_to = Label(text="is equal to", font = ("Arial", 20))
is_equal_to.config(padx = 10, pady = 10)
is_equal_to.grid(column = 0, row = 2)

km = Label(text="Km", font = ("Arial", 20))
km.config(padx = 10, pady = 10)
km.grid(column = 3, row = 2)

result = Label(text="0", font = ("Arial", 20))
result.config(padx = 10, pady = 10)
result.grid(column = 2, row = 2)

# Entry

entry = Entry(width = 10)
entry.grid(column = 2, row = 0)


# Button

button = Button(text="Calculate", command = calculate)
button.config(padx = 10, pady = 10)
button.grid(column = 2, row = 3)

window.mainloop()


Link(s) to work: PyCharm file.

Day 28: March 10th 2022

Thoughts:

import tkinter
import time
import math
from tkinter import *
# ---------------------------- CONSTANTS ------------------------------- #
PINK = "#e2979c"
RED = "#e7305b"
GREEN = "#9bdeac"
YELLOW = "#f7f5dd"
FONT_NAME = "Courier"
WORK_MIN = 25
SHORT_BREAK_MIN = 5
LONG_BREAK_MIN = 20
reps = 0
timer = NONE

# ---------------------------- TIMER RESET ------------------------------- # 
def reset_timer():
    global reps
    reps = 0
    window.after_cancel(timer)
    timer_title.config(text = "TIMER", fg = GREEN)
    check.config(text = "")
    canvas.itemconfig(timer_text, text="00:00")

# ---------------------------- TIMER MECHANISM ------------------------------- # 
def start_timer():
    global reps
    reps += 1
    if reps % 8 == 0:
        count_down(5) # Replace with long break time
        timer_title.config(text="BREAK", fg = RED)
    elif reps % 2 == 0:
        count_down(3) # Replace with short break time
        timer_title.config(text = "BREAK", fg = PINK)
    else:
        count_down(10) # Replace with work time
        timer_title.config(text = "WORK", fg = GREEN)

# ---------------------------- COUNTDOWN MECHANISM ------------------------------- # 
def count_down(count):
    count_min = math.floor(count / 60)
    count_sec = count % 60
    if count_sec == 0:
        count_sec = "00"
    elif count_sec < 10:
        count_sec = f"0{count_sec}"

    canvas.itemconfig(timer_text, text = f"{count_min}:{count_sec}")
    if count > 0:
        global timer
        timer = window.after(1000, count_down, count - 1)
    else:
        start_timer()
        mark = ""
        for i in range(math.floor(reps/2)):
            mark += "✔"
            check.config(text = mark)

# ---------------------------- UI SETUP ------------------------------- #
# Window
window = Tk()
window.title("Pomodoro Timer")
window.config(padx = 100, pady = 50, bg = YELLOW)

# Canvas
canvas = Canvas(width = 200, height = 224, bg = YELLOW, highlightthickness=0)
tomato_png = PhotoImage(file="tomato.png")
canvas.create_image(100, 112, image = tomato_png)
timer_text = canvas.create_text(103, 130, text = "00:00", fill = "white", font = (FONT_NAME, 35, "bold"))
canvas.grid(column = 2, row = 2)

# count_down(5)

# Title
timer_title = Label(text = "TIMER", bg = YELLOW, fg = GREEN, font = (FONT_NAME, 50))
timer_title.grid(column = 2, row = 0)
timer_title.config(padx = 10, pady = 10)

# Start Button
start_button = Button(text = "Start", command = start_timer)
start_button.grid(column = 0, row = 3)
start_button.config(padx = 5, pady = 5)

# Reset Button
start_button = Button(text = "Reset", command = reset_timer)
start_button.grid(column = 3, row = 3)
start_button.config(padx = 5, pady = 5)

# Check Marks
check = Label(bg = YELLOW, fg = GREEN)
check.grid(column = 2, row = 4)

window.mainloop()

Link to work: Pycharm Day 28 file. REFER TO THIS!

Day 29: March 10th 2022

Thoughts:

New things learned = "".join() function

grid(columnspan = )

from tkinter import messagebox (messagebox.())

entry.delete(0, END) <- removes the last typed thing

Don't forget UI setup:

UI Setup
window = Tk()
window.title("Password Manager")
window.config(padx = 20, pady = 20)

# Logo Image
canvas = Canvas(width = 200, height = 200)
logo_png = PhotoImage(file = "logo.png")
canvas.create_image(100, 100, image = logo_png)
canvas.grid(column = 2, row = 0)

Link to work: PyCharm File Day 29

Day 30: March 15th 2022

Thoughts: Learned JSON write, load, update and errors/exceptions

try: function

except: print("Error Found")

except FileNotFoundError:

except KeyError as error_message:

else:

If exceptions occur, else block doesn't get read

raise ErrorClass <- Raising your own error e.g TypeError("This is a made up error")

• usually for inputs that are unrealistic e.g unrealistic heights etc.

Can be nested inside an if statement

JSON Data: JavaScriptObjectNotation

write = json.dump()

read = json.load()

update = json.update()

Create New Dictionary
new_data = {
        web_input: {
            "email": user_input,
            "password": pass_input,
        }
    }
Create JSON File
with open("stored_passwords.json", "a") as storage:
	json.dump(new_data, storage, indent = ) <- indent for readability

with open("stored_passwords.json", "r") as storage:
	json.load(storage) <- converts json to dictionary


            with open("stored_passwords.json", "r") as storage:
                # Reading old data
                data = json.load(storage)
                # Updating old data with new data
                data.update(new_data)
		# Adding new data
            with open("stored_passwords.json", "w") as storage:
                json.dump(data, storage, indent=4)
		
Link to work: PyCharm File
