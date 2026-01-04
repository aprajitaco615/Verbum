# Verbum
A word guessing game that helps you hone your vocabulary  
## 🎮 Verbum Key Features  
### 🗄️ Persistent Data Storage  
* Uses MySQL to store user profiles, including usernames, total plays, wins, and high scores.  
### 📚 Automated Word Bank  
 * Automatically generates a comprehensive database of 6-letter words and their meanings using the NLTK (Natural Language Toolkit) library.  
### 🎯 Core Gameplay Mechanics  
 * Standard word-guessing logic with a limit of 6 attempts allowed per round.  
### 🎨 Visual Feedback  
 * Provides colored feedback for each letter to indicate if it is in the correct position, wrong position, or not in the word.  
### 🛡️ Input Validation  
 * Robust checking system to ensure word length is correct, the word exists in the dictionary, and to prevent repeated guesses.  
### 📈 Dynamic Scoring System  
 * Calculates scores based on the number of attempts taken and updates the user's high score in the database automatically.  
### 🎓 Educational Integration  
 * Displays the definition/meaning of the secret word at the end of each round to aid in vocabulary building.  
### 🔄 Session Management  
 * Offers a seamless experience allowing users to choose between playing another round or quitting the application.  
### ⚙️ Self-Initializing Setup  
 * Includes a first-time setup process that automatically builds the necessary database and local word files on the first run.  
## 📦 Verbum Dependencies  
### External Libraries  
​mysql-connector-python: Required for connecting to the MySQL database and performing CRUD operations on user profiles.  
​nltk: The Natural Language Toolkit, used specifically for downloading the 'words' and 'wordnet' corpora to generate the word bank.  
​termcolor: Used to provide colored terminal output for visual feedback during gameplay.  
### ​Standard Libraries  
​random: Used for selecting a secret word at random from the database.  
​os: Used for file path checks, specifically to see if the word database file already exists.  
​sys: Used for advanced terminal control, such as moving the cursor and clearing lines to keep the UI clean.  

© 2026 aprajitaco615 All Rights Reserved
