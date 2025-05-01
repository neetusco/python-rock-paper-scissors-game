# Rock, Paper, Scissors – Python Game (Jupyter Notebook)

This is a beginner-friendly interactive game built using a **Jupyter Notebook**, where you play Rock, Paper, Scissors against the computer. It’s a fun way to practice Python fundamentals like randomization, conditional logic, and user input handling.

---

## Project Objective

This project is designed to:
- Strengthen core Python skills
- Practice using Jupyter Notebooks for interactive coding
- Reinforce understanding of control flow with `if/elif/else`
- Provide a hands-on, playful learning experience

---

## View the Notebook

You can explore the full interactive notebook directly on GitHub:  
[`rock_paper_scissors.ipynb`](rock_paper_scissors.ipynb)

To run the game interactively:
- Launch it in **Jupyter Notebook**, or
- Upload it to **Google Colab** for a browser-based experience.

---

## Game Instructions

1. Open the `.ipynb` file in a Jupyter Notebook interface.
2. Run the cells sequentially.
3. When prompted, enter your move: **"Rock"**, **"Paper"**, or **"Scissors"**.
4. The computer will randomly select its move.
5. The game will determine and display the result:
   - You win!
   - You lose!
   - It’s a tie!
6. If your input is invalid, the program will alert you to try again.

---

## Game Logic

The computer's move is randomly selected using Python's `random` module. The result is calculated based on traditional Rock-Paper-Scissors rules using conditional logic.

### Rules:

- **Rock** beats **Scissors**
- **Scissors** beats **Paper**
- **Paper** beats **Rock**

| Your Choice | Computer's Choice | Result     |
|-------------|-------------------|------------|
| Rock        | Scissors          | You Win    |
| Rock        | Paper             | You Lose   |
| Paper       | Rock              | You Win    |
| Paper       | Scissors          | You Lose   |
| Scissors    | Paper             | You Win    |
| Scissors    | Rock              | You Lose   |
| Same        | Same              | Tie        |

---

## How to Run the Game

### Jupyter Notebook (locally)
1. Ensure you have Anaconda installed (it includes both Python and Jupyter Notebook).

2. Download or clone this repository to your local computer.

3. Open Anaconda Navigator from your Start Menu (Windows) or Applications (Mac).

4. In Anaconda Navigator, click "Launch" under the Jupyter Notebook option.

5. A browser window will open showing your file explorer. Navigate to the folder where you saved rock_paper_scissors.ipynb.

6. Click the notebook file to open it. Then, run to play the game!
