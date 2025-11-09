# Guess The Number 🔢

A classic interactive command-line game implemented in Python. The program selects a random integer within a defined range, and the user tries to guess it, receiving hints (too high or too low) along the way.

## 🚀 Getting Started

### Prerequisites

You only need a working installation of **Python 3**.

### Installation and Running

1.  **Clone the repository** to your local machine:
    ```bash
    git clone [https://github.com/YourUsername/guess-the-number-python.git](https://github.com/YourUsername/guess-the-number-python.git)
    cd guess-the-number-python
    ```
    (Replace `YourUsername` with your actual GitHub username)

2.  **Run the script** from your terminal:
    ```bash
    python GuessTheNum_User_.py
    ```

3.  **Play the game!** The script, as written, will prompt you to guess a number between 1 and 100.

## 🛠️ How It Works

The core logic is within the `guesse(x)` function in `GuessTheNum_User_.py`:

1.  A random number is generated between 1 and the input value `x` (currently set to 100).
2.  A `while` loop continues until the user's guess matches the random number.
3.  Conditional checks (`if/elif`) provide feedback: "Your to low" or "Your to high."
4.  The loop exits upon a correct guess, and a congratulatory message is printed.

## ✨ Future Enhancements

* Allow the user to set the range (min/max numbers).
* Add a counter to track the number of guesses.
* Implement a "high scores" feature.

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file (if you create one) for details.
