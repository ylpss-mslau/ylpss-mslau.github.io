# AI Camera Quiz Demo

- [Demo AI camera test](ai_camera_demo.html) ([Source Code](https://github.com/ylpss-mslau/ylpss-mslau.github.io/blob/main/ai_camera_demo.html))
  - Capturing camera image
  - Using TensorFlow mode trained by Teachable Machine to get an result (A, B, C, or D)
- [Demo online quiz](demo_quiz.html) ([Source Code](https://github.com/ylpss-mslau/ylpss-mslau.github.io/blob/main/demo_quiz.html))
  - Showing the basic idea of the game without AI camera
  - It fetches question bank in JSON format via a URL.
  - It shows 10 random questions and the user can answer.
  - At the end, it shows the final score.
- [Demo JSON question bank](questions_v1.json) ([View in onine editor](https://jsoneditoronline.org/#left=url.https%3A%2F%2Fylpss-mslau.github.io%2Fquestions_v1.json))
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
