# Guess the Number

Guess the Number is a small web game. The computer picks a secret number, and you guess it using higher and lower hints. Choose a range of 1 to 100 (7 guesses) or 1 to 1000 (10 guesses). It shows your guess history and counts your wins.

Live demo: https://YOUR-USERNAME.github.io/Guess-the-Number/

Built with: HTML, CSS and JavaScript.

What this project shows: The best strategy is binary search. Always guess the middle of the range that is still possible, and each guess cuts the remaining numbers in half. That is why 7 guesses always work for 1 to 100 (2^7 = 128) and 10 guesses always work for 1 to 1000 (2^10 = 1024). Binary search is one of the most common algorithms in computer science, and it is how computers find items in sorted lists quickly. The game picks its secret number with `Math.random()` and checks each guess against it.

What I'm learning from it: I'm studying how the code picks a random number in the chosen range, how it checks each guess and shows a higher or lower hint, and how the number of allowed guesses is tied to the range.
