***Week 1: Introduction to Programming and Web Design***

# DAY 1

  ## NOTES:
  
	Focuses:
		Beginners' introduction to programming and programming languages as a concept
		Setting up development environments
		Intro to web development, website/app structure
		Intro to markup languages and markup concepts
		Intro to programming languages and programming concepts

	  The "Intro To Programming" lesson is optional for students who aren't familiar with programming topics  
    at all. It looks unnecessarily long, but that's mostly because it is the bullet points I would put in a  
    PowerPoint slideshow. In reality, the lesson itself could probably fit in under 10 minutes, and doesn't  
    require any notes to be taken by students. Its purpose is to introduce beginners to the concept of  
    programming and what programming languages are used for, as well as the different kinds of programming  
    languages.

  ## TOPICS:

### OPTIONAL - Intro To Programming: What Is Programming? (10 minutes)
* What Is Programming?
   * Programming allows humans to give computers instructions
   * Programming is what drives all new apps, websites, and programs
   * Programming is one of the most valuable skills in the world
   * Programming spans every context that computers are used for 
     * High-speed microcontrollers in vehicles and sensors
	 * Low-performance, low-energy mobile devices
	 * Mid-performance personal computers
	 * Internet servers and databases
	 * Machine learning and AI
* What Are Programming Languages
   * Communicate with and issue instructions to computers--specifically the computer's processor
   * Different languages have different features and capabilities
   * Some languages are context-specific, like Solidity or JavaScript, and can't be used outside of that context
   * Other languages are fairly universal, like C++, and are used almost everywhere
   * Some languages are very easy to learn, such as Python, while others are very technical and complicated, such as C
* High-Level vs Low-Level Languages
   * Low-level languages are languages close to--or directly in contact with--the computer's hardware
     * This category primarily involves assembly, a language designed to give human-readable names to binary machine code instructions
	 * Assembly directly controls the registers, memory usage, and operations performed inside a computer's processors
	 * Assembly is extremely difficult to use and is also extremely dangerous, as it has no safeguards in place to detech and prevent self-destructive code
	 * Assembly is rarely used thanks to high-level languages like C++, but it is still used in fields involving microcontroller engineering and other low-level hardware
   * High-level languages are languages that simplify low-level languages to make programming easier and safer
     * C and C++ are the most powerful and valuable high-level languages, as they are very close to the hardware and run very light
     * Almost all programming and development today is done in high-level languages
	 * Different languages are designed for different purposes and contexts
	 * JavaScript, Python, and Solidity are high-level languages that we will be exploring in this course
* Compiled vs Interpreted Languages
   * Compiled Languages:
     * Must be turned into machine code by a compiler program before they can be run
	 * Often downloaded onto a user's machine, and run directly on its processors
	 * Fast and light, but incompatible with other operating systems, and cannot be easily changed
	 * Must be developed and compiled for Windows, Mac, and Linux machines separately
	 * Compiled languages are more compatible with the Waterfall development approach
   * Interpreted Languages:
     * Turned into machine code by an interpreter program line-by-line as they are read
	 * Not run directly on the machine's processors
	 * The interpreter runs on one processor, which requires many operations to be run for every line of code that it interprets
	 * Interpreted languages are slow and inefficient compared to compiled languages
	 * Can be run by any machine without needing different versions of the same program, as each machine has its own interpreter
	 * Used primarily for websites and web applications, particularly those that don't need to process huge amounts of data
* Programming vs Markup Languages
   * Programming Languages:
     * Issue logical and computational instructions to the computer
	 * Often involves applied mathematics, Boolean logic, and complex systems
	 * Defines variables, functions, objects, and data the computer can work with
	 * Allows a computer to make decisions based on the data it has
	 * Used for creating programs, web applications, and scripts
   * Markup Languages:
     * Instruct a computer how to format and display a document
	 * Decorate and align text, links, headers, and other components
	 * Used primarily in HTML and CSS in web development, but also in Markdown (MD) files for documentation
* Other Languages (Not important, just fun to know about)
   * Machine Code
     * Also called binary code, this is the 1's and 0's all code is reduced to that only a machine can understand
   * Assembly Languages
     * One step above binary code, this uses human-readable opcodes, hexadecimal memory addresses, and base-10 numbers to make machine code readable
   * Query Languages
     * Used for accessing and using databases
   * Scripting Languages
     * Used by command line interfaces and terminals for automating various tasks
   * Esoteric Languages (Esolangs)
     * Created as jokes by bored programmers, either for silliness, creative inspiration, or pure malice


### Development I: Code Editors vs Integrated Development Environments (IDEs)
* What's The Difference Between a Code Editor and an IDE?
  * Code editors make coding easy and smooth, but cannot run code
  * Editors are less ideal for large-scale development, and better for working on individual files
  * IDEs aren't as flexible as code editors, but allow code to be run and tested
  * IDEs are more complex and designed for large-scale development projects
* Downloading and Installing Development Tools
   * PyCharm (5 minutes)
     * Suggested PyCharm Extensions:
   * Visual Studio Code (5 minutes)
     * Suggested VSCode Extensions:
       * Colonize (Auto adding semicolon)
       * HTML5 Boilerplate
       * One Dark Pro Theme
       * Path Intellisense
       * Color Highlight
       * CSS Peek
   * Node.js / NPM (5 minutes)


### Programming Fundamentals I: Data Types, Variables, Input/Output (15 minutes)
* Data Types: (5 minutes)
   * Numbers (2 minutes)
     * Floats vs Integers
	 * Signed vs Unsigned Integers
   * Strings (1 minute)
   * Booleans (1 minute)
   * Tuples vs Sets (2 minutes)
   * Bytes and Addresses (1 minute)
     * Memory locations are expressed in bytes
   * Null / None
     * Why do we need a data type for nothing?
* Variables: (5 minutes)
   * What are variables? (1 minute)
   * The variable assignment operator: = (1 minute)
   * The importance of choosing good variable names (2 minutes)
   * Assigning variables to each other (1 minute)
* User Input/Output: (5 minutes)
   * Examples of I/O in other languages (1 minute, just to show differences)
     * C++: cin, cout
	 * Python: input(), print()
	 * JavaScript: prompt(), console.log()
   * Input: input() (3 minutes)
     * "Press any key to continue" prompt (1 minute)
     * Storing user input strings (1 minute)
     * Storing user input numbers (1 minute)
   * Output: print() (2 minutes)
     * Using print for debugging (1 minute)
     * Mixing variables and strings (1 minute)
* Importing Modules:
   * Keyword: import

```
	Python Lab: Hello World, Greeting Message (10 minutes)
	Project Component: Character's Name
```

### Python Practice
* Temperature Converter
   * Prompt the user to enter a temperature in Celsius using input()
   * Convert the temperature to Fahrenheit using the formula F = (C * 1.8) + 32
   * Print out the converted temperature using print()

* Name and Age
   * Prompt the user to enter their name and age using input()
   * Store the name and age in separate variables
   * Print out a message that includes the user's name and age using print()

* Area Calculator
   * Prompt the user to enter the dimensions of a rectangle (length and width) using input()
   * Calculate the area of the rectangle using the formula area = length * width
   * Print out the calculated area using print()

* Tip Calculator
   * Prompt the user to enter the total bill amount and the desired tip percentage using input()
   * Calculate the tip amount and the total amount (including tip) using the formulas tip = bill_amount * tip_percentage and total_amount = bill_amount + tip
   * Print out the tip amount and the total amount using print()


### Web Development I * Components Of A Web App (5 minutes)
* Website/App Components
   * HTML (1 minute)
   * CSS (1 minute)
   * JavaScript (1 minute)
   * Web Server (1 minute)
     * Servers vs Clients
   * Node.js
* DNS (1 minute)
   * IP Addresses
   * Domain Names
*Web Development II * Intro To HTML (5 minutes)*
* A Brief History of HTML (2 minutes)
* HTML Structure and Syntax (3 minutes)

### HTML I (15 minutes)
* Creating a simple HTML page
* Head Section:
   * Page Title: title
   * Metadata/Information: meta
   * External Resource Links: link, src
   * Move to Body Section
     * Brief explanation
* Text:
   * Headings: h1 through h6
   * Paragraphs: p
   * Line Breaks: br
* Non-Semantic Text Tags:
   * Bold: b
   * Italicized: i
   * Underlined: u
   * Strikethrough: s
   * Center: center
* Lists:
   * Unordered Lists: ul
     * Can set item markers in html but bad practice
   * Ordered Lists: ol
   * List Items: li
* Images:
   * Inserting Images: img, src, alt
* Anchors/Hyperlinks:
   * Hyperlinks: a, href
* Tables:
   * Quick touch on this topic 
   * Creating Tables: table
   * Table Rows: tr
   * Table Headers: th
   * Table Data Cells: td
   * Specific uses: Tabular data
     * Data Tables
     * Screen readers
     * Headers, rows, columns 
     * Scope, Caption

```
HTML Lab: Personal Website HTML (20 minutes)
```


### HTML Practice:
  * Personal Profile Page: Create a web page that includes a page title, a brief introduction using header and paragraph elements, and a photo of yourself using the image element.
  
  * Favorite Recipe Page: Create a web page that includes a page title, a header with the name of the recipe, a list of ingredients using an unordered list, a list of instructions using ordered lists, and a photo of the finished dish using the image element.

  * To-Do List Page: Create a web page that includes a page title, a header with the title "To-Do List," and a list of tasks using unordered lists and list items. Include hyperlinks to external resources that may be helpful for completing some of the tasks.

  * Favorite Book List Page: Create a web page that includes a page title, a header with the title "Favorite Books," and a list of book titles using an ordered list. Include hyperlinks to the books' descriptions or reviews using the anchor element and the href attribute.

  * Bucket List Page: Create a web page that includes a page title, a header with the title "Bucket List," and a list of items that you want to do or achieve in your lifetime using unordered lists and list items. Include hyperlinks to external resources that may help you achieve your goals.


---



# DAY 2:
  ## NOTES:
	Focuses:
		Discussing development models, particularly Agile and Waterfall
		Discussing the usefulness of diagrams in designing programs and apps
		Using LucidChart to create a use case diagram for a CYOA game

### Development II: Development Models and Planning (20 minutes)
* Development Phases: (5 minutes)
   * Analysis
   * Design
   * Implementation
   * Testing
* Development Models: (5 minutes)
   * Waterfall
	 * Development proceeds in a straight line from beginning to end
     * Large-scale systems that need careful design
	   * Used where system failures / errors pose high risk to end user
	 * User needs and technologies are well understood and will not change
	 * Once completed, system cannot be changed
	 * Commonly used for complex infrastructure systems, where changes are impossible or pose a high risk of introducing failures
	   * Example: Financial and banking systems, engineering projects, Solidity smart contracts
   * Agile
     * Development cycles through all phases for each component in a spiral pattern
	 * Small-scale or changing systems that need fast implementation and iteration
	   * Used where system failures / errors pose low risk to the end user
	 * User needs and technologies are not fully understood, or are constantly changing
	 * Frequent coordination and feedback with stakeholders and customers during development
	 * Components are changed as new needs arise, and every component runs through the 4 development phases individually
	 * Commonly used for web design and gaming applications, where updates and improvements are easy to roll out, and consequences of errors are low
	   * Example: Early access games, mobile applications
	 * We will focus almost exclusively on the Agile model in this course
* Diagrams (10 minutes)
   * Why do we need diagrams? (1 minute)
     * Visually model complex systems and interactions
	 * Provide an visual blueprint for developers to follow
	 * Reveal potential flaws and weaknesses in the system before it is built
   * Diagram Types: (10 minutes)
     * Use Case
	   * Models requirements of a system by showing how actors interact with it 
	 * Class
	   * Models static structure of a system by showing its classes, interfaces, and their relationships
	 * Object
	   * Models a "snapshot" in time of the objects in a system, their attributes, and their relationships at that moment
	 * Sequence
	   * Models dynamic behavior of a system by showing interactions between objects over time. Shown as a sequence of messages passed between objects.
	 * State Machine
	   * Models behavior of individual objects/classes by showing different states, events that trigger state transitions, and actions performed during each state
	 * Activity
	   * Models flow of control or data by showing activities or processes performed, decisions made, and control/data flow between activities
	 * Component
	   * Models physical structure of a system by showing the components, their interfaces, and their relationships and dependencies with each other

### Development Lab: Personal Website Analysis
   * Analyzing Desired Components of The Website
### Development Lab: Intro To Figma
   * Creating UI Layouts In Figma For Personal Website

### Development Lab: Text-Based Adventure Game Analysis and Design (5 minutes)
   * Analyzing Desired Features (5 minutes)
     * Main menu, scenes with choices, in-game items, basic combat system
### Development Lab: Intro To LucidChart (15 minutes)
   * Creating Flow-Charts In LucidChart
   * Creating CYOA Game Component Diagrams
     * Main menu, scenes, characters, in-game items
   * Creating CYOA Game Class Diagrams
     * Player character, scenes, enemy NPCs
   * Creating CYOA Game State Machine Diagrams
     * Transitions between scenes and combat


### Programming Fundamentals II: Functions, Arithmetic, Branches (20 minutes)
* Functions and Scope:
   * What are functions? (2 minutes)
     * Functions are sections of code that can be ran repeatedly
	 * Internal logic
	   * May do something entirely self-contained
	   * May make changes to outside variables
	   * May call other functions
     * Can take input parameters
	 * Can return output parameters
   * Declaring a Function (1 minute)
     * Most languages use function keyword
	   * Pseudocode: function greetMe(name) = return "Hello " + name;
	 * Python: def
	   * Python: def greetMe(name): return ("Hello", name)
   * Input and output parameters (3 minutes)
     * Input parameters
	   * Pass-by-value vs pass-by-reference
	     * PBV: A copy is made of the input variable
		 * PBR: The original input variable is used
	   * Python uses pass-by-assignment
	     * Simple "immutable" objects like numbers, strings, and tuples are passed by value
		 * Complex "mutable" objects like lists, dictionaries, sets, and user-defined objects are passed by reference
		 * Don't worry about this distinction for now
	  * Output parameters
	    * Returning vs returning values
		  * Use return to stop a function and return to the code that called it
		  * Add a value after return to pass the value back to the code that called the function
   * Calling functions (1 minute)
     * Passing and receiving variables to and from a function
	   * Variables given to a function as inputs don't need to share the same name as the function's definition inputs
	   * Optional parameters
	     * Not important to remember right now, but it'll be crazy useful when you do need it
     * A brief discussion on recursive functions
   * Object Methods and Dot Notation
     * Examples: .append() for lists, .upper() for strings
* Arithmetic Operators: +, -, *, **, /, //, %, () (5 minutes)
   * Addition/Subtraction (1 minute)
   * Multiplication/Exponentiation (1 minute)
   * Division, Integer Division, Modulo (3 minutes)
     * Computers are imprecise at dividing floating point numbers
     * Why do we need integer division? (1 minute)
     * Why do we need the modulus operator? (1 minute)
   * Parentheses (1 minute)
   * Order of Operations (1 minute)
   * Compound Assignment Operators: +=, -=, *=, /= (1 minute)
   * Converting Math Equations To Code (2 minutes)
     * Code is written on one line, equations are not
	 * Use variables to store results of complex calculations
* Comparison Operators: <, <=, >, >=, ==, != (3 minutes)
   * Boolean Data Type Review (1 minute)
* Branching Logic: if, elif, else (6 minutes)
   * If: if (1 minute)
   * Else If: elif (2 minutes)
   * Else: else (1 minute)
* Boolean Reasoning (2 minutes)
* Boolean Logic Operators: and, or, not
   * Boolean Logic And Computers (2 minutes)
	  * Boolean logic is the core of all computing technology
	  * Computers run on "logic gates"
	  * Logic gates are simulated in programming
   * And Gates: and (1 minute)
   * Or Gates: or (1 minute)
   * Not Gates: not (1 minute)

### Python Lab: Math Formula Functions, Parity Checking, Input Branches
```
	Creating functions for common geometric formulas (5 minutes)
	Creating a function to check a number's parity (evenness/oddness) (3 minutes)
	Creating a series of functions that branch on user input (5 minutes)
```

### Python Practice
* Write a Python program that asks the user to input their name and age, and then prints out a message saying "Hello [name], you are [age] years old!".

* Write a Python program that asks the user to input a number, and then prints out whether the number is positive, negative, or zero.

* Write a Python program that asks the user to input their age, and then checks whether they are eligible to vote. If the user is 18 or older, the program should print "You are eligible to vote". If the user is younger than 18, the program should print "You are not yet eligible to vote".

* Write a Python program that asks the user to input a number, and then checks whether that number is even or odd. If the number is even, the program should print "The number is even". If the number is odd, the program should print "The number is odd".

* Write a Python program that asks the user to input their weight in pounds, and then converts their weight to kilograms and prints out the result. Note that 1 pound is equal to 0.453592 kilograms.

* Write a Python function called calculate_average that takes in three numbers as input and returns the average of the three numbers.

* Write a Python function that takes in two numbers and returns the sum of their squares. The function should be called sum_of_squares and should take in two parameters, num1 and num2.

* Write a Python function called reverse_list that takes in a list of integers and returns the list in reverse order. For example, if the input list is [1, 2, 3, 4], the output should be [4, 3, 2, 1].
   * Hint: Python lists have a built-in method for this exact purpose. Use Google to find it!

* Write a Python function called is_palindrome that takes in a string and returns True if the string is a palindrome (meaning it reads the same forwards and backwards), and False otherwise. For example, if the input string is "racecar", the function should return True, but if the input string is "hello", the function should return False.
   * Hint: There is a very funky solution to this problem that involves string slicing. Google it and try it out!

* **Recursive Challenge:** Write a recursive Python function called calculate_factorial that takes in a number as input and returns the factorial of that number. The factorial of a number is the product of all positive integers up to and including that number. For example, the factorial of 4 is 4 x 3 x 2 x 1 = 24. This is one of the easiest recursive functions to write, but like all recursive functions it is still difficult to code if you've never done it before!
  * Remember: A recursive function is a function that calls itself repeatedly to perform a task
  * Hint: Each iteration of this function will follow the formula m = n * (n - 1), where n is the input variable, (n - 1) is the recursive function call, and m is the returned value



### HTML Tags II (20 minutes)
* Div and Span:
   * Grouping Elements: div, section, header, nav, main, footer
     * Retouch on semantic/non-semantic
   * Applying Styles: span
     * Retouch on semantic/non-semantic
* Forms:
   * Creating Forms: form
   * Input Types: input (text, checkbox, radio, submit, date/time)
   * Labeling Form Inputs: label
   * Dropdown Menus: select
   * Dropdown Options: option
* Additional Tags:
   * Horizontal Line: hr
   * Block Quotes: blockquote
   * Preformatted Text: pre
     * ASCII Art, Code blocks

```
HTML Lab: Contact Form
Mini-Project: Applying Div Tags To Website
```

### Web Development III: Intro to CSS (60+ minutes)
* What is CSS?
   * The Box Model and Stylesheets
   * External Stylesheets vs Internal Stylying vs Inline Styling
     * External > Internal > Inline (Order of popularity)
   * Hierarchy
     * Cascading
     * CSS Specificity
* Two good resources:
* Introducing W3Schools for CSS
   * https://www.w3schools.com/css/default.asp
* Introducing CSS Tricks
   * https://css-tricks.com/

### CSS I: Selectors, Text, and Background
* CSS syntax and selectors
   * Selectors: Element, ID, and Class
   * Nesting and Combinators
* BEM Naming Convention
   * What is BEM?
   * The benefits of BEM
   * BEM syntax and usage
* Units of Measurement
   * Absolute Units: px, pt, mm, cm, in
   * Relative Units: em, rem, vw, vh
   * Best practices for unit selection
* Text and Fonts
   * Font Family and Size
     * Google Fonts, Importing and Using
   * Font Style and Weight
   * Text Color and Alignment
   * Line Height
   * Text formatting
     * Why we steer away from formatting text inside the html itself.
       * Refer back to span tag
       * Keep content (HTML) and presentation (CSS) separate
       * Accessibility
* Backgrounds
   * Background Color
   * Background Image and Repeat
   * Gradients (linear and radial)  
   * Background Size and Position
     * Sizing and positioning gradients  

``` 
CSS Lab: Adding color, background, font style to website (10 minutes)
```

---

# DAY 3:
### Development III: Implementation Phase (2 minutes)

### Programming Fundamentals III: Loops And Algorithms (10 minutes)
 * Loops:
   * For Loops: for()
	  * Python uses "for-each" loops
	    * Iterating over a list of values
	  * Common loop in Python: for x in range(y)
	    * Calling a function y times
   * While Loops: while()
      * While loops are used when the number of loop iterations is unknown, or if the loop is terminated by user input
	  * Use a while loop when you need your loop to keep running when a certain condition is true, not necessarily a counter
	  * While loops can easily turn into infinite loops, so be prepared to kill the program
   * Do-While Loops: do while
	  * Python has no do-while loop, but we can build one manually
	  * You'll know when you need a do-while when you need one, otherwise don't worry about it
 * Loop Control:
   * Breaking out/early: break
   * Continuing to the next iteration: continue

### Python Lab: Game Main Menu, Count To N (20 minutes)
 * Count To N:
   * Using a for loop and range to count from 0 to N
 * Main Menu:
   * Use a while loop, branches, and conditionals to create a menu
   * Main menu must have "New Game" and "Exit Game" options
   * When user types "Exit Game", break out of the loop
   * When user types "New Game", call the new_game function that prompts for their name

### Python Practice
```
* Write a Python function called print_table that takes in a number as input and prints out a multiplication table for that number. For example, if the input is 3, the output should be:
	1 x 3 = 3
	2 x 3 = 6
	3 x 3 = 9

* Write a Python program that asks the user to input a password, and then checks whether the password contains any uppercase letters. If the password does contain uppercase letters, the program should print "Password is strong". If the password does not contain any uppercase letters, the program should print "Password is weak".

* Write a Python program that generates a list of 10 random numbers between 1 and 100, and then uses a for loop to print out only the even numbers in the list.

* Write a Python program that asks the user to input a number, and then uses a while loop to print out the multiplication table for that number. The program should keep asking for a number until the user enters "exit".

* Write a Python program that generates a list of 20 random numbers between 1 and 100, and then uses a for loop to print out the sum of all the numbers in the list. If the sum is greater than 500, the program should break out of the loop and print "Sum is too large". If the sum is less than or equal to 500, the program should continue to the next iteration.
```


## Python Mini-Project
### Hangman Game
  **Description:** 
	In Hangman, players try to guess letters in a random secret word without making too many wrong guesses. Normally, the game is played by drawing a noose and filling in stick-figure body parts with each wrong guess, but that would be tedious to code--so we won't do that part (unless you want to try it). We will create the same game using a list filled with random words, a function that randomly chooses one of the words to be the secret word, a counter variable for remaining guesses, a function that builds and stores the partially-completed word, a function that prints the partially-completed word, and a function that determines if the player made a correct or incorrect guess.

	Your design choices are not important, the important thing is if they work. You can optimize and improve upon your design later, so don't worry about creating the perfect design right away. You will need to apply all your Python knowledge to pull this game off. This mini-project will give you a new appreciation for how much thought and effort goes into even the simplest tasks in programming.

  	*An activity diagram is provided in the supplemental materials to illustrate how this game works*

  **Details:**
   * Import the "random" module, we will need it for the randint() function
   * Create a list from the following words:
	[Serendipity, Mellifluous, Quintessential, Ephemeral, Magnanimous, Ethereal, Luminous, Ubiquitous, Sagacious, Insouciant, Irresolute, Propinquity, Inscrutable, Ineffable, Garrulous, Halcyon, Extemporaneous, Pernicious, Discombobulate, Pulchritudinous]
   * Create a function to pick a random secret word from the list using the randint(0, 19) function as the list index, and store the secret word in a global variable
   * Create a function that prompts the player to guess a character, adds the character to a guessed characters list, and then passes the character to a checking function. Store the returned value of the checking function inside a local variable, which will be True if the guess was correct, and False if it was not.
     * If the returned value is False, then decrement the player's remaining guesses
	 * If the returned value is True, then call a function to update the partially-completed word
	 * If the player's remaining guesses is 0, then print "YOU LOSE!!!" 10,000 times to the console
	 * If the partially-completed word is equal to the secret word, then print "YOU WIN!!!" 10,000 times to the console
   * Create a function that determines if a letter exists in the secret word
     * If the letter does not exist in the secret word, then return False
	 * If the letter exists in the secret word, then return True
   * Create a function that updates and stores the partially-completed word
     * If the player has not guessed a letter yet, then replace it with an underscore "_" character
	 * If the player has already guessed a letter, then add the secret word's character to the partially completed word
	 * Examples of function outputs: "S___nd_p_ty", "__lc_on", "Garrul_us", "___________"
   * Create a game loop that repeatedly calls the user input function until the game is either won or lost

  **Hints:**
  * You will need to create a function that iterates over the secret word and compares each letter to the letter passed to the function. This will be the most complex part of the game, as this mechanism will need to perform a few different tasks:
    * It must add the player's guess to a list of guessed letters
	* It must compare the player's guess to each character in the secret word, and decide whether to update the partial word or decrement their remaining guesses variable
	* It must call a function that updates the partial word when a correct guess is made
  * You will also need to create an algorithm that updates the partially completed word when the player makes a correct guess. This algorithm will compare each character in the secret word to the entire list of guesses made by the player, and if a match is found it adds the letter to the partial word. If not match is found, then it adds an underscore instead.
  * Remember: You can iterate over strings with a "for x in y" loop, and you can join two strings together by using the + operator.



*Web Development IV: Combining JS, HTML, and CSS (10 minutes)*
	<While we don't cover JS yet, students will be aware it exists, so we can show how to link it>
  * Linking CSS and JS to HTML
  * JavaScript and CSS manipulation of HTML elements

*CSS II: Layout and Positioning*
  Layouts and Positioning
  * Display Property: block, inline, inline-block, fixed, sticky, none
  * Position Property: static, relative, absolute, fixed
  * left, right, top, bottom Properties
  * Floats and Clearing
  Wrappers and Containers
  * The role of containers in layouts
  * Nesting and specificity
  * The box-sizing Property
  Borders
  * Border Color, Style, and Width
  * Border Radius
  Flexbox
  * The Flexbox Model
  * Flex Containers and Items
  * Flex Direction
  * Flexbox Properties: justify-content, align-items, align-content, flex-wrap, flex-flow

```
HTML/CSS/JS Lab: Calculator App (20 minutes)
  * User input and button elements
  * Creating a calculator app
```

---



**DAY 4:**
 * Development IV: Testing (10 minutes)
   * Unit Tests
   * Testing "Fringe Conditions"
 * Development Lab: Unit Testing Calculator Program (20 minutes)

 * Programming Fundamentals IV: Data Structures (10 minutes)
   * Lists
     * Arrays
       * Arrays as an ordered collection of data
	   * Array properties (indexes, length)
	   * Accessing array elements
	   * The problem with arrays: Adding and removing elements
	 * Fixed-length vs dynamic arrays
	   * All arrays are stored in contiguous memory
	   * Fixed arrays are never resized, and thus very efficient
	   * Dynamic arrays must be resized and copied when new elements are added
   * Other Kinds Of Lists (Not Important To Know)
	 * Linked Lists
	 * Doubly Linked Lists
	 * Circular Arrays / Circular Linked Lists
	 * Stacks
	   * LIFO: Last In, First Out
	   * Most arrays
	 * Queues
	   * FIFO: First In, First Out
   * Dictionaries / Mappings
     * Unordered collections of data
     * Key-value pairs and lookup tables
	 * Lookup tables are the most efficient data structure
   * Classes vs Objects
     * Classes are prototypes, objects are instances
	   * Classes are a "blueprint" to create objects
	   * Objects are living instances of classes in memory
     * Everything in Python is an object with object methods
	   * String methods: .upper(), .lower()
	   * Number methods: .is_integer()
	   * List methods: .append(), .extend(), .insert(), .remove(), .pop(), .index(), .count(), .sort(), .reverse()

 * Python Lab: Lists, Dictionaries, Classes, Objects (10 minutes)
   * Lists and list methods
   * Classes and class methods
     * Initializing a class object with __init__
 * Python Lab: Adventure Game Objects
   * Weapons (Damage, Durability)
   * Health Potions (HP Restore)
   * Player Character (HP, Inventory, Abilities, Game State)

*CSS III: CSS Resets and BEM Methodology*
* CSS Reset
   * What is a CSS Reset?
   * Why use a CSS Reset?
   * Examples of popular CSS Resets
* BEM Naming Convention
   * What is BEM?
   * The benefits of BEM
   * BEM syntax and usage


**DAY 5:**
*Development V: Version Control and Github (10 minutes)*
* Introduction to Git and Github
* Basic Concepts of Git
  * Commits
  * Branches
  * Merges
    * Creating a Github account and setting up a new repository
*Development Lab: Git (10 minutes)*
* Setting Up and Configuring Git
* Basic Git Commands
  * status
  * add
  * commit
  * push
  * pull
  * merge
  * branch
  * common issues

Programming Fundamentals V: Random Numbers (5 minutes)
 * Random Numbers in Programming
   * Applications of random numbers
 * Random Numbers in Python

*Python Lab: Adventure Game Combat System (25 minutes)*
 * Implementing A Randomized Combat System:
   * Random Range: randrange()
   * Hit Chance
   * Damage


**WEEKEND OPTIONAL PRACTICE:**
 * Interactive Image Gallery
   * Create interactive image gallery using HTML, CSS, and JS
   * Use JS to control display of images and captions
   * Add interactivity, such as zooming, or clicking to enlarge image


