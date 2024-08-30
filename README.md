This is a simple quiz game that loads questions from a dataset and allows the user to answer them in sequence. The game keeps track of the score and displays it at the end.

The program uses three main components:
1. Question class: representing a single quiz question with its text and answer.
2. Data: containing a list of dictionaries with quiz questions and their correct answers
3. QuizBrain: which manages the quiz logic, including presenting questions, checking answers, and keeping track of the score.

How It Works
1. The program iterates through the question_data list. It creates instances of the Question and adds them to the question_bank list.
2. An instance of QuizBrain is created with the question_bank as its input.
3. The quiz continues as long as there are questions remaining
4. The next question is presented to the user, takes his input, checks if it is correct, and updates the score.
5. Once all questions are answered, a completion message is printed along with the user's final score.

This project is a basic implementation and can be expanded to include more features, such as saving scores, categorizing questions, or providing hints.
