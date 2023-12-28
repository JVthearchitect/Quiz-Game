# Quiz-Game

This Python script represents a quiz game that tests your knowledge with a set of questions. The script utilizes three main components: `Question` class, `QuizBrain` class, and a user interface (`QuizInterface`) to interact with the quiz.

## Components

### `Question` Class
The `Question` class represents a question object, containing the text of the question and its correct answer.

### `QuizBrain` Class
The `QuizBrain` class manages the quiz logic. It takes a list of `Question` objects and tracks the user's score and progress through the quiz.

### `QuizInterface` Class
The `QuizInterface` class provides a user interface for the quiz, allowing the user to answer questions interactively.

## Usage

1. Clone the repository or download the script.
2. Make sure you have the required modules: `question_model`, `data`, `quiz_brain`, and `ui`.
3. Run the script:

    ```bash
    python quiz_game.py
    ```

4. Answer the questions displayed in the user interface.
5. After completing the quiz, the script will print your final score.

## Customization

You can customize the quiz questions by modifying the `question_data` in the `data` module. Each question is represented as a dictionary with "question" and "correct_answer" keys.

```python
# Example question_data format
question_data = [
    {"question": "What is the capital of France?", "correct_answer": "Paris"},
    {"question": "Which planet is known as the Red Planet?", "correct_answer": "Mars"},
    # Add more questions as needed
]
```
