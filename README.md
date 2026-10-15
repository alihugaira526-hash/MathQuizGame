# C++ Math Quiz Game

An interactive console-based math quiz application built in C++ that tests users with random arithmetic problems across customizable difficulty levels and operation types.

## 🚀 Key Features
* **Customizable Quiz Length:** Choose how many questions you want to answer per round (1 to 10).
* **Multiple Difficulty Levels:** Select from Easy, Medium, Hard, or a Mixed level with randomized number ranges.
* **Diverse Operations:** Test your skills in Addition, Subtraction, Multiplication, Division, or a Mixed operations mode.
* **Interactive Feedback:** Visual console color changes (Green for correct answers, Red for incorrect answers) with immediate result prompts.
* **Performance Summary:** Displays a final Pass/Fail evaluation along with total right and wrong answers at the end of each quiz.
* **Replay Option:** Play multiple rounds consecutively without restarting the program.

## 🛠️ Tech Stack & Concepts Applied
* **Language:** C++
* **IDE & Toolchain:** Microsoft Visual Studio (MSVC) or any standard C++ compiler
* **Core Concepts:** 
  * Custom `structs` (`stQuestionInfo`, `stQuizInfo`) for grouping related data.
  * `enum` types for clean state management (`enQuestionLevel`, `enOperationType`).
  * Procedural modular design using separate functions for game logic, input validation, and screen formatting.
  * Pseudo-random number generation (`rand`, `srand`).
  * System command utilities for screen clearing and console color styling.

## 💻 How to Run
1. Open the project solution or create a new C++ project in **Visual Studio**.
2. Paste the source code into your `main.cpp` file.
3. Build and run the program by pressing `Ctrl + F5`.
