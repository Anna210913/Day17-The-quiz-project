# Day17-The-quiz-project
We learnt how to build a **Quiz Game** using OOP! Through this project we were able to strengthen our understanding of classes, objects, attributes and methods while making a fun true/false quiz program.

This quiz game asks the user True/False questions, checks their answers, and keeps track of their score. It continues until all questions are answered, then displays the final score.

Rather than keeping everything in one script, we broke the project into **separate classes**:

| File | Purpose |
|------|--------|
`question_model.py` | Defines the `Question` class (each question object has text + answer) |
`data.py` | Stores the quiz questions data |
`quiz_brain.py` | Handles question flow, checking answers, tracking score |
`main.py` | Creates question objects, runs the quiz |

# What I learned:

- How to create my own class in Python
- Understanding **attributes** (variables inside a class)
- Understanding **methods** (functions inside a class)
- What `__init__()` (class constructor) does
- How to create multiple objects from a class
- How to access attributes & call methods using dot notation
- How to structure code across multiple files using OOP
- The benefits of using OOP to organize logic cleanly
