Creating a quiz app is an excellent way to learn the fundamentals of web development. In this tutorial, we will build a Quiz App that features a timer, allowing users to take a timed quiz with multiple-choice questions. The app will use HTML for the structure, CSS for styling, and JavaScript for functionality, including the timer and score tracking.
______________________
About index.html 

* `<html>`: The root element that contains the entire webpage.

* `<style src="style.css"></style>`: This tag is intended to link a CSS file, but it should be `<link rel="stylesheet" href="style.css">` instead. As written, it won't load the CSS correctly.

* `<body>`: Contains all the visible content of the page.

* `<div class="quiz-container">`: A wrapper div that holds the whole quiz interface.

* `<div class="timer">Time Left: <span id="time">30</span>s</div>`: Displays a countdown timer with the time value inside the `<span id="time">` so it can be updated dynamically.

* `<div class="question">Question will appear here</div>`: Placeholder where the quiz question text will be displayed.

* `<div class="options"></div>`: Empty container where the answer options (like buttons or radio inputs) will be inserted dynamically.

* `<div class="result">Your score: <span id="score">0</span></div>`: Shows the user’s current score, with the number inside the `<span id="score">` for easy updates.

* `<button class="restart-btn">Restart Quiz</button>`: A button users can click to restart the quiz.

* `<script src="script.js"></script>`: Links an external JavaScript file that will handle quiz logic like timing, questions, scoring, and interaction.
________________
About script.js file

* The `<div class="question">` displays each quiz question from the `quizData` array.
* The `<div class="options">` holds dynamically created `<button>` elements for each answer choice, letting users click to select an answer.
* The `<span id="time">` inside the timer `<div>` shows a countdown starting at 30 seconds for each question.
* When an answer button is clicked, the code checks if it matches the correct answer and updates the score.
* If time runs out or all questions are answered, the `<div class="result">` becomes visible to show the final score inside `<span id="score">`.
* The `<button class="restart-btn">` appears to let the user restart the quiz, resetting everything and showing the first question again.
* The script manages all these elements by updating their text content, showing/hiding them, and handling user interactions smoothly to create an engaging timed quiz experience.
______________________
 About style.css file


* `body`: Sets the overall font, background color, and centers the entire quiz container both vertically and horizontally using flexbox. It removes default margin and padding for a clean layout.

* `.quiz-container`: Styles the main wrapper `<div>` for the quiz with a white background, rounded corners (`border-radius`), subtle shadow (`box-shadow`), padding inside, and limits the width for readability.

* `.question`: Styles the `<div class="question">` that shows the quiz question text, making the font a bit larger and adding space below it.

* `.options`: Styles the container `<div class="options">` that holds all answer buttons, arranging them vertically with spacing between (`gap`).

* `.option`: Styles each answer `<button>` inside `.options` with padding, border, rounded corners, and a pointer cursor. It also adds smooth color changes when hovered to highlight interactivity.

* `.timer`: Styles the timer `<div class="timer">` with bigger font size and an orange color to make it stand out.

* `.result`: Styles the results `<div class="result">` with a larger green font, but it is hidden initially (`display: none`) and shown when the quiz ends.

* `.restart-btn`: Styles the restart `<button class="restart-btn">` with a blue background, white text, rounded corners, padding, and a pointer cursor. It is also hidden by default and appears after the quiz finishes. On hover, its background color darkens for feedback.
__________________
Uses of Quizz App Project
* ✅ **Quick learning and revision**
* ✅ **Classroom teaching and assessments**
* ✅ **Employee training and onboarding**
* ✅ **Skill and language practice**
* ✅ **Fun and entertainment (trivia games)**
* ✅ **Social engagement and challenges**
* ✅ **Customer interaction for businesses**
* ✅ **Daily brain training or habit building**
