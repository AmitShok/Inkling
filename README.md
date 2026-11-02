# Inkling

A word-guessing game where you pick the secret word. Any word works, including made-up ones, from 2 to 30 letters. Set how many guesses your friends get, add a hint if you like, and send them the link.

Play it at **https://amitshok.github.io/Inkling/**

## How it works

- Everything lives in `index.html`: no build step and no dependencies.
- The puzzle (word, guess count, hint, your name) is scrambled into the part of the link after `#`, so there's no server or database.
- Orange = right letter, right spot. Blue = in the word, wrong spot. Grey = not in the word.

## Run it locally

Open `index.html` in a browser, or in VS Code use the Live Server extension and click **Go Live**.
