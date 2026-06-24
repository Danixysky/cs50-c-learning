# cs50-c-learning
My AI Engineering Journey

Welcome to my learning repository! I am documenting my path from learning fundamental computer science logic to becoming an AI Engineer.

This repository documents my journey learning C through CS50. It contains exercises and small programs covering variables, user input, conditionals, and loops as I build my programming foundation for AI engineering.

My Philosophy 🧠 

I am not just memorizing syntax; I am training my brain to read code like a machine and structure logic. I use AI tools for syntax generation, but I design the architecture and control flow myself. I don't memorize where the semicolons go; I learn why the machine needs to make a decision. I am particularly interested in my problem-solving ability, breaking down concepts, and also combining concepts to achieve a certain goal.

🏗️ Level 1: Variables & State (The Boxes)

Before a program can do anything, it needs a place to store information.

- int: A box for whole numbers (e.g., int score = 50;)

- string: A box for text/words (e.g., string name = "Daniel";)

- bool: A box that only holds true or false.

Getting User Input (The Funnels)

To make a program interactive, we ask the user for information and immediately drop their answer into a box.

int price = get_int("Enter the price: ");

🔀 Level 2: Control Flow (The Machine's Brain)

Code normally runs straight down from top to bottom. "Control Flow" is how we tell the computer to skip lines, make decisions, or teleport back to the top.

1. if / else (The Fork in the Road)

Used when the computer needs to make a decision exactly once.

Logic: The computer asks a True/False question. If True, it goes down Path A. If False, it goes down Path B.

Example: "If the final score is over 100, print 'You win!'. Otherwise, print 'Thanks for playing!'"

2. while loops (The Bouncer / The Bus Stop)

Used when you want to repeat an action, but you do not know how many times it needs to be repeated.

Logic: The Bouncer checks your ID. If the condition is True (price != 0), you step inside the loop. When you hit the bottom, you teleport back to the Bouncer.

The Trap: You MUST change the variable inside the loop (ask for a new price, add to the score), otherwise the Bouncer sees the exact same ID forever, creating an infinite loop!

3. for loops (The Track Coach)

Used when you know exactly how many times an action needs to repeat before the loop even starts (like exactly 5 rounds of a game). It packs three instructions into one line:

The Setup: Where do I start? (int round = 1;)

The Question: When do I stop? (round <= 5;)

The Math: How do I move forward? (round = round + 1)

🛠️ Projects & Logic Exercises

Here are the raw files documenting my progress. In each of these, I focused on translating plain-English client requirements into structural code logic.

1. The Game Show Tracker

Goal: Track a player's score over exactly 5 rounds and determine if they win a prize.

Logic Used: Definite iteration (for loop) to manage exact round counts, combined with conditional logic (if/else) for the final prize decision.

2. The Self-Checkout Machine

Goal: Create a running total for an unknown number of scanned items until the user triggers a stop.

Logic Used: Indefinite iteration (while loop) checking for a specific break condition (price != 0), followed by a state update (applying a discount).

Continuously updating as I progress into Level 3: Arrays, Memory Management, and AI Integration.

