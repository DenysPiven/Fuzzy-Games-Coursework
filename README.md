# Applying the Generalization Principle to Solve Fuzzy Matrix Games — Coursework (2023)

**Coursework (2023):** "Applying the Generalization Principle to Solve Fuzzy Matrix Games", 1st year of the master's program (group SMPR-1), Taras Shevchenko National University of Kyiv, Faculty of Computer Science and Cybernetics. Author: Denys Piven. Supervisor: Prof. Serhii Mashchenko, Dr. Sc. (Phys.-Math.). The coursework text (Ukrainian) is in [`thesis/`](thesis/Applying_the_Generalization_Principle_to_Solve_Fuzzy_Matrix_Games.pdf), its LaTeX source in [`tex/`](tex/main.tex). Continued in the master's thesis [Fuzzy-Games-with-Fuzzy-Strategies-Master-Thesis](https://github.com/DenysPiven/Fuzzy-Games-with-Fuzzy-Strategies-Master-Thesis) (2024).

This project focuses on applying the generalization principle to solve fuzzy matrix games using Java implementation. The primary objective is to solve linear programming problems with fuzzy numbers. To accomplish this, we have utilized the optimization capabilities of the Apache Commons Math library.

### Main references
- S.-T. Liu, C. Kao. Solution of Fuzzy Matrix Games: An Application of the Extension Principle. International Journal of Intelligent Systems, 2007.
- M. Larbani. Non cooperative fuzzy games in normal form: A survey. Fuzzy Sets and Systems 160 (2009) 3184–3210.

### Prerequisites
- Java 20
- Apache Commons Math 3.6 or higher

### Installation

- Clone the repository from GitHub
- Download Apache Commons Math library from https://commons.apache.org/proper/commons-math/download_math.cgi
- Extract the downloaded folder and copy the commons-math3-3.6.1 into the lib folder of the project
- Open the project in your preferred IDE (e.g. Eclipse, IntelliJ IDEA)
- Add the commons-math3-3.6.1 folder to the project's build path

### Usage

To use the project, follow these steps:

- Create a file named input.txt and place it in the input_output folder.
- In the input.txt file, enter a matrix with fuzzy numbers following the example provided.
- Run the project.
- The program reads input.txt, parses data to a fuzzy matrix, creates systems of linear inequalities in alpha cuts, and solves them using FuzzySolver (number of alpha cuts can be adjusted).
- The result will be written to a file named output.txt in the input_output folder using FuzzyWriter.
- Additionally, a visualization graph of the points will be generated in SVG format with the name image.svg.

### Contributing
You are welcome to contribute to this project by submitting pull requests or raising issues related to bugs or feature requests.

### License
Copyright (c) 2023 Denys Piven