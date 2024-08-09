# Flash Cards App
This Flash Cards app is a simple and interactive tool designed to help you learn Korean vocabulary. Built with Python using the Tkinter library for the graphical user interface and pandas for data management, this app displays flashcards with Korean words and their English translations.

## Features
Randomized Flashcards: The app displays Korean words randomly from a pre-defined list.
Word Tracking: The app keeps track of words you've learned and those you still need to study. Words marked as known are removed from the learning list.
Automatic Flip: Each flashcard flips automatically after 3 seconds, revealing the English translation.
Progress Persistence: The app saves your progress, allowing you to resume where you left off even after closing the app.
## How It Works
Start Learning: Upon launching the app, a random Korean word will be displayed.
View Translation: The card will automatically flip after 3 seconds, revealing the English translation.
Mark as Known: If you know the word, click the checkmark button. The word will be removed from your learning list.
Skip to Next Word: If you're unsure of the word, click the cross button to skip to the next one.
Save Progress: Your progress is automatically saved. The app will create a file named words_to_learn.csv to store the remaining words.
