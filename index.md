# AI Camera Quiz Demo

- [Demo AI camera test](testing)
  - Capturing camera image
  - Using TensorFlow mode trained by Teachable Machine to get an result (A, B, C, or D)
- [Demo JSON question bank](testing/questions_v1.json)
  - [View this JSON file in onine editor](https://jsoneditoronline.org/#left=url.https%3A%2F%2Fylpss-mslau.github.io%2Ftesting%2Fquestions_v1.json)
  - Prompt to generate the demo question bank:
    ```
    Generate 30 MC questions for secondary 1 level students in Hong Kong to learn the use of prepositions.
    Give the questions in JSON format of an array of objects, each object with the following structure:
    {
      "question": "I go to school ______ bus.",
      "options": {
        "A": "by",
        "B": "on",
        "C": "in",
        "D": "to"
      },
      "correct_answer": "A"
    }
    ```
    - Content to generate: MCQ
    - Target audience: S1 students
    - Context: Hong Kong
    - Purpose: Learning prepositions
    - Format: JSON with example provided
