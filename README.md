#  Rubik’s Cube Solver – AeroHack 2025 Submission

This project provides a complete solution to solve a **3x3 Rubik’s Cube** using Python in **Google Colab**. It combines:
* Beginner Layer-by-Layer (LBL) solving strategy (easy to understand)
* Kociemba’s Two-Phase Algorithm (advanced & optimal)

Developed and submitted for AeroHack 2025, Computer Science Track.

---

##  Problem Statement

Design and implement an algorithm to solve any scrambled 3x3 Rubik’s Cube using valid cube rotations. The solution should simulate real-world cube logic and aim for correctness and efficiency.

---

##  Features

- Cube modeled using dictionaries and lists
- Applies all 18 valid moves: U, D, F, B, L, R (and primes)
- Uses `kociemba` algorithm for optimal solving
- Works 100% in **Google Colab** (no setup required)
- Outputs correct move sequence to solve any scramble

---

## 🛠️ How to Run (Google Colab)

🔗 [Click here to open the notebook in Colab](https://colab.research.google.com/github/avidipriyanka/rubiks-cube-solver/blob/main/rubiks_cube_solver.ipynb)

Then:

1. Click `Runtime > Run all`
2. View the solution output in the last cell
3. Optionally, change the scramble and rerun

---

## 🧪 Sample Input & Output
Scramble: R U R' U R U2 R'
Cube String: UUUUUUUUURRRRRRRRRFFFFFFFFFDDDDDDDDDLLLLLLLLLBBBBBBBBB
Solution: R L U2 R L' B2 U2 R2 F2 L2 D2 L2 F2
## 📁 Files Included

- `rubiks_cube_solver.ipynb`: Python notebook (Colab-ready)
- `example_output.txt`: Sample output from solving(colab-ready)
- `README.md`: Project summary and instructions
- `Rubiks_Cube_Solver_AeroHack2025.pptx`: Final presentation slides

---

##  Technologies Used

- **Python 3.10+**
- **kociemba** (Python module for optimal Rubik’s cube solving)
- **Google Colab** (for execution)
- **GitHub** (for sharing and version control)

---

##  Author

- Name: Avidi Priyanka  
- Track: Computer Science – Cube Solver  
- Event: AeroHack 2025  
- GitHub Repo: https://github.com/avidipriyanka/rubiks-cube-solver.git



