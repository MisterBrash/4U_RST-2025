# Gr. 12 Final Project (RST)

###### ICS4U - Mr. Brash 🐿️

Final Project (Rich Summative Task) worth 30% of the overall mark.

- [General Outline](#general-outline)
- [Requirements](#requirements)
- [Project Ideas](#project-ideas-in-absolutely-no-particular-order)
- [Suggested Timeline](#suggested-timeline)
- [Rubric](#rubric)
- [Resources](#resources)

### General Outline:

The final project encompasses your understanding of the course material. It must include two _**or more**_ of the following:
- Sorting or Searching
- Recursion (with or without divide & conquer)
- Complex Data Structures (multi-dimensional arrays / matrices)
- Abstract Data Types (pseudo-objects using key,value pairs)
- Object Oriented Programming (Classes)
  - Required
- The Model-View-Controller (MVC) design pattern
  - Back-to-Front-End Development (HTML)
  - (_optional_) Usage of the `<canvas>` element or [the p5js library](https://www.p5js.org)
  - (_optional_) Collisions & movement

This final project will be an application (or game) built using JavaScript, HTML, & CSS. It is worth 30% of your final grade.

#### ⚠️ If you want to use some other programming library or language, contact your teacher ASAP.

---

### Requirements:
([Rubric](#rubric) available below)
- [Project proposal](https://forms.gle/3z8Tjw9L243XD41g6) including minimum expectations
- Draft User Interface (storyboarding)
- Draft data structure / pseudo code overview
- Students _must_ commit to GitHub at the end of every period 2 class and commit messages _must_ be meaningful or at least not random/gibberish
  - Save now, save often
- Obvious entry to the application or game
  - Instructions available, if required (do not assume the user understands)
  - User does not need to speak to developer at all to use the application
- Proper commenting and structure of code
- Student does not utilize tutorial or pre-baked code to create final project
  - Simple algorithms (ie. randInt) or CSS examples excluded
- **Due no later than Tuesday, June 17th @ 9:50am**

### Project Ideas (in absolutely no particular order)

- [Minesweeper](https://minesweeper.brash.ca) (add your own twist?)
- Battleship
- Backgammon
- Solitaire (or other card games)
- Side-scroller / platformer
- Pacman!
- [Chess](https://chess.adamts.me/) or Checkers (a good challenge)
- Your own Tetris
- [2048](https://misterbrash.github.io/2048_Student_Example/)
- [Space Invaders](https://elgoog.im/space-invaders/)
- Recreate or reimagine a twist on [a 1980's arcade game](https://www.free80sarcade.com/galaga.php)!
- [Crossword puzzle _generator_](https://crosswordlabs.com/)
- [Word search _generator_](https://thewordsearch.com/maker/)
- [Maze generator](https://www.mazegenerator.net/) (and solver?)
  - This uses recursion


### _Suggested_ Timeline

| Pick Game / App | Storyboarding & Code Structure | Code | Test & Fix | Submit _by_|
|:----:|:----:|:----:|:----:|:----:|
|By Fri. May 16th| May 20-22 | May 23 - June 12 | June 12-16 |Tues June 17th @ 9:50am |

### Step 1: Proposal
[Complete this Google Form](https://forms.gle/3z8Tjw9L243XD41g6) to the best of your ability. Expect potential changes or discussion with your teacher within a day or two.

### Step 2: Draft GUI (Storyboarding)
On paper, a whiteboard, or a digital image (you could use [Excalidraw](https://excalidraw.com/)) create and include a draft design for the front-end of the program. It should contain any and all input/control from the user as well as extra pages or information panels. Try to be detailed and as complete as possible in order to make coding simpler. Place images or content in the [Step_2](Step_2) folder.

(It's **ok** if the final product does _not_ match your draft. Do not modify the draft afterward.)

### Step 3: Data Structure & Pseudocode
Now that you have a front-end, you can begin designing the data structure and functions for your program.
- What sort of data structure will you need - arrays? A matrix? **Classes**?
  - Don't forget - OOP is a _requirement_.
  - Does your OOP involve _inheritance_?
  - Do any need to be _global_ variables?
  - Are you over-complicating your data structure? (don't do that)
- Are you using a canvas? [P5js](https://www.p5js.org)? Other HTML elements?
- Do you need event listeners?
  - What are they?
    - If keys or mouse, what information do you need like key codes or mouse buttons?
  - What function(s) will those listeners be calling?
- What is the functional structure of the program?
  - What helper functions do you think you'll need?

Inside the [Step_3](Step_3) folder, upload a text file or image of your planning and pseudocode. Try to work in an organized fashion so you can read your own work!

(It is **ok** if your code structure changes - especially your data structurer or major algorithms, this is all part of the planning.)

### Step 4: Code, code, code
If you planned the GUI and the code structure properly, the coding should be easier at this point.
- Create the basic GUI. **Don't worry about colours, fonts, design** - don't even worry about specific photos (you can replace them later). Give your elements meaningful IDs and create a layout that mimics your storyboards.
  - Have you noticed changes you'll need to make? That's ok, make them!
- I cannot stress enough how important it is to avoid making it _look good_ at this point. **Get it working first!**
- Enable the event listeners and make sure they work.
- Create the data structure you planned.
- Write the functions one-by-one, **testing as necessary**.
- Keep notes on changes you foresee or extra functions and algorithms you did not realize you would need during your planning stages. (_Do not change your storyboards or pseudocode for these adjustments_)
- Test, test, test...
- **COMMENT YOUR CODE AS YOU GO!**


### Step 5: Testing & Final Fixes
Test your program extensively and often. Have _someone else_ test your program extensively. Make the appropriate bug fixes or changes to your program. Listen to your tester(s) and consider their input. Just because you thought of it, doesn't mean it's best layout or setup.
Then test it again. And again.

### Submit!


## Rubric:
This rubric is a work in progress and _input from the class is encouraged_

|Expectation Description|Level 1|Level 2|Level 3|Level 4|
|---|---|---|---|---|
|**Project proposal**|Proposal is vague, incomplete, and/or not submitted on time.|Proposal includes some description and/or some final expectations and is submitted on or near the due date.|Proposal is submitted on-time, includes a description of the program and final expectations.|Proposal is submitted on-time (or early) and includes description, expectations, UI examples, and more.|
|**Draft User Interface**|Draft UI is not representative of the chosen application, is incomplete or missing key features.|x | x|x |
|**Data structure, plan, pseudocode**|Data structure and planning is incomplete or missing key details/features.|x|x|x|
|**Code**| Code is... | x | x | Code is clean & structured, functions and data are named clearly & appropriately. Code is structured neatly, tabbed properly, and easy to read or follow. Globals and listeners are declared at the top with functions declared in an appropriate style and order.|
|**Code Style**|x|x|x|Variable and function names are clear and easily understood. Code structure follows style or organization demonstrated in class. Student does not use new or over-engineered code structures beyond the course material or expectations. No use of spaghetti code or repetition of code (helper functions employed).|
Code Documentation | x | x | x | Developer has supplied a thorough documentation of code including file header(s) and algorithm descriptions. Variables and data structure are explained, along with functions and helper-functions or classes. Comments are concise but give detail, written in a grammatically correct and pleasing style.|
|Application Instructions| x | x | x | The application includes how-to instructions for the user, clearly identifying how to use the program, along with the various modes or functions of the application. Instructions are not obtrusive or in-your-face, they are easy to read and easy to understand.|
|Application Usability| x | x | x | The program/game works as expected or described. The user is able to understand and use the application without any assistance from the developer or otherwise. Buttons and actions respond as expected, the program entrance and exit are obvious or easy to navigate, and instructions or assistance is available within the application itself. |
|Application Completion| x | x | x | The program is _complete_ in the sense that there is a beginning, middle, and end. No errors or otherwise lack of program _end_ is noticeable. Either through winning or losing, saving or quitting, and all listed or linked functionality is as described. No features are left out. |

---

### Resources:
(updated when new ones are found or made)
- [Class website](https://www.brash.ca)
- [w3schools](http://w3schools.com)

- ♠️ [Regular deck of 54 cards PNG files](https://drive.google.com/drive/folders/1hYgBIqgznqmL_cvZnpEsaWlCR1SjDxnD?usp=sharing)
- ⚓ [Low-Res Battleship graphics](https://drive.google.com/drive/folders/0BzyP6cTwQ57eQWFLRjJ0TnFkUXc?resourcekey=0-T7t2LVthJId6vlsmrtwKUg&usp=sharing)
- 🖼️ [p5js reference](https://p5js.org/reference/)
- 📽️ [Canvas Element & 2D Arrays slideshow](https://docs.google.com/presentation/d/e/2PACX-1vS-hC9xZtpAwELck59sNa1Syq5JqAfhQe2ixrD6VnvXH4KUNTU5f_hIPCxnAdx2YAVNrVaRmxJ44lsm/pub?start=false&loop=false&delayms=3000)


<br><br>
🐿️

<br><br><br><br><br><br><br><br><br><br>
