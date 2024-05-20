# Data-Structure-File-I-O
# Oddonacci Sequence Calculators

This project provides implementations to compute the Oddonacci sequence using different approaches: tail-recursive, linear-recursive, and multiple-recursive methods. The Oddonacci sequence is similar to the Fibonacci sequence but with each term being the sum of the three preceding terms.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Performance](#performance)
- [Contributing](#contributing)
- [License](#license)

## Overview
The Oddonacci sequence is defined as:
- Oddonacci(1) = 1
- Oddonacci(2) = 1
- Oddonacci(3) = 1
- Oddonacci(n) = Oddonacci(n-1) + Oddonacci(n-2) + Oddonacci(n-3) for n > 3

This project includes three implementations to compute the Oddonacci numbers:
1. **Tail-Recursive**
2. **Linear-Recursive**
3. **Multiple-Recursive**

## Project Structure
The project contains the following Java files:
- `TailRecursiveOddonacci.java`: Implementation using tail recursion.
- `LinearOddonacci.java`: Implementation using linear recursion.
- `MultipleRecursiveOddonacci.java`: Implementation using multiple recursion.

Each implementation also writes the results and execution times to a text file and prints them to the console.

## Getting Started
### Prerequisites
- Java Development Kit (JDK) 8 or later

### Cloning the Repository
```bash
git clone https://github.com/your-username/OddonacciCalculators.git
cd OddonacciCalculators

# Usage
Compiling the Code
javac main/TailRecursiveOddonacci.java
javac main/LinearOddonacci.java
javac main/MultipleRecursiveOddonacci.java

#Running the Programs
java main.TailRecursiveOddonacci
java main.LinearOddonacci
java main.MultipleRecursiveOddonacci

Each program will generate an output file (OddoOutTailRecursive.txt, OddoOutLinear.txt, OddoOutMultiple.txt) containing the Oddonacci numbers for values from 5 to 200 in increments of 5 along with the computation time in nanoseconds.

Performance
The time complexity of each implementation varies:

Tail-Recursive: Linear complexity O(k)
Linear-Recursive: Linear complexity O(k)
Multiple-Recursive: Exponential complexity O(3^k)
Due to the exponential time complexity, the multipleOddonacci implementation is inefficient for large values of k and is mainly included for educational purposes.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
This project is licensed under the MIT License - see the LICENSE file for details.

Happy Coding!
