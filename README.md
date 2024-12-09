script rundown

types of fish: i compiled a list of fish of various kinds and sizes (small, medium, large, and huge). these sizes determine the number of points scored when they are caught.

casting the line: the player "casts the line" by pressing enter, an action simulated with input(). when it's time to catch a fish, a random number generator gets first dibs on determining if actually a fish will be caught at all. if caught, another random number generator selects from our list of fish types.

scoring: the score is based on the size of the fish caught:

small: 1 point

medium: 3 points

large: 5 points

huge (more like a shark): 10 points

game over: after the user has cast the line a predetermined number of times (5), the game is over; however, the player isn't just cast away but is given a score and some personalized feedback.

running the game :

save the script: copy and paste the code into a text file named fishing_game.py.

navigate to the directory: open a terminal and use cd to navigate to the directory where you saved fishing_game.py.

run the game:

in the terminal, type:
    
python fishing_game.py
    
if you're using python 3 specifically, and your system has both python 2 and python 3 installed, use:
    
python3 fishing_game.py

more info 

fish variety: you can add more types of fish or modify the existing ones.
number of casts: change num_casts = 5 to any other number to adjust the game length.
probability of catching a fish: adjust the probability of catching a fish by changing the condition in if random.random() < 0.7: (currently a 70% chance).
