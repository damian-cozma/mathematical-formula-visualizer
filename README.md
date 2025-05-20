# Mathematical Formula Visualizer/Editor

This repository showcases a tool for visualizing and editing mathematical formulas. With this application, users can input mathematical expressions in ASCII format, such as `1/2 + sqrt(5)`, and the application will render a graphical representation of the formula, including addition, subtraction, multiplication, division, and various functions like square root and logarithms, drawn pixel by pixel.

## Features

- **User-Friendly Input:** Enter mathematical formulas using simple ASCII notation.
- **Accurate Visualization:** Converts ASCII input into visually accurate mathematical symbols and structures.
- **Graphical Output:** Generates images of mathematical formulas, making them easy to understand and present.
- **Main Data Structure**: Binary Expression Tree (converts user input from infix notation to postfix notation for building the expression tree).
- **Technologies**: Given the project's focus on developing algorithmic thinking in a university setting, primitive technologies were employed to avoid excessive templating. The project utilized:
  - `iostream` for basic input/output operations.
  - `graphics.h` for graphical capabilities.
  - `conio.h` for console input/output handling.
  - `cstring` for string manipulation functions.
  - `cstdlib` for general-purpose functions.
  - `cstdio` for input/output functions.
- **Programming language:** C++ (CodeBlocks IDE)


## Purpose

This project is intended to demonstrate my abilities in creating applications that can process and visualize mathematical formulas. The source code is not publicly available.

### Collaborator

This project was developed hand in hand with [David Cimpoesu](https://github.com/david-cimpoesu), emphasizing collaborative effort and teamwork throughout our first semester of computer science degree.

### User Interface in Romanian

The user interface (UI) of this application is in Romanian, but it demonstrates the functionality effectively without requiring knowledge of the language.

## Showcase

### Main Menu

![fotor-2024062920113](https://github.com/DamianCozma/FormulaEditor/assets/149274508/342c0fb5-5a20-43b0-959d-bdd0874dc76c)

- Translation: "Formula | Expression | Tree | Instructions"

### Error Showcase: Pressing "Arbore" or "Expresie" Without Input

<img width="1197" alt="image" src="https://github.com/DamianCozma/FormulaEditor/assets/149274508/681019cf-aaac-449e-a01f-d407bc202ce3">

- Translation: "You haven't introduced any formula yet!"

### Typing a Function

<img width="1198" alt="image" src="https://github.com/DamianCozma/FormulaEditor/assets/149274508/c3b62500-00e9-4714-88e5-e455bd2dab39"> <br>

- In order to type in the mathematical formula, you will need to click on "Manual" - which stems from 'manually introducing the formula' - as there are 3 default examples you can click on to demonstrate how the application works.
<br>

<img width="1196" alt="image" src="https://github.com/DamianCozma/FormulaEditor/assets/149274508/c16e8f53-4293-425e-802f-be072a6c1db4">

### Displaying the Expression

- After typing the function, pressing "Expresie" displays the mathematical expression.

<img width="1195" alt="image" src="https://github.com/DamianCozma/FormulaEditor/assets/149274508/87057206-8857-42b2-bd19-c73e01d63efb">

### Displaying the Tree

- Pressing "Arbore" shows the tree representation of the function.

<img width="1196" alt="image" src="https://github.com/DamianCozma/FormulaEditor/assets/149274508/24f6fc8c-7346-41b0-ae31-060103384f73">

### Handling Incorrect Input

- If an incorrect formula is entered, such as `1//2`, which should be `1/2`, the application will indicate the error and prompt for correct input.

<img width="1196" alt="image" src="https://github.com/DamianCozma/FormulaEditor/assets/149274508/d202deb0-81de-4256-9f2e-0465c4198764">

- Translation: "Wrong formula! Check the instructions and make sure you have respected the rules"

### Save

- The saving feature is simple: you click on the 'Save' button, and a .png file will be saved in your .CPP directory.

<img width="1241" alt="image" src="https://github.com/DamianCozma/FormulaEditor/assets/149274508/d8219725-a7f5-492f-a826-2dd1252acecf">

### Closing remarks
This project marks my first venture into the world of software development at university, approached with enthusiasm and determination despite our initial lack of experience in applied software development. We managed to build a useful and efficient application that taught us numerous lessons and technical improvements. This experience has been invaluable in my learning journey, preparing me for future challenges in the field of computer science.
