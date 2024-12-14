<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mujeeb's Quizzes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            margin: 0;
        }
        .quiz-category {
            background-color: #ffffff;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .quiz-category h2 {
            color: #4CAF50;
        }
        .quiz-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
        }
        .quiz-item {
            background-color: #f9f9f9;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .quiz-item a {
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Mujeeb's Quizzes!</h1>
    <p>Test your knowledge across various topics: Math, Geography, and more!</p>
</header>

<div class="container">
    <div class="quiz-category">
        <h2>Math Quizzes</h2>
        <div class="quiz-list">
            <div class="quiz-item"><a href="#">Quiz 1: Basic Algebra</a></div>
            <div class="quiz-item"><a href="#">Quiz 2: Geometry</a></div>
            <div class="quiz-item"><a href="#">Quiz 3: Calculus</a></div>
            <!-- Add more math quizzes here -->
        </div>
    </div>

    <div class="quiz-category">
        <h2>Geography Quizzes</h2>
        <div class="quiz-list">
            <div class="quiz-item"><a href="#">Quiz 1: World Capitals</a></div>
            <div class="quiz-item"><a href="#">Quiz 2: Country Flags</a></div>
            <div class="quiz-item"><a href="#">Quiz 3: Landmarks</a></div>
            <!-- Add more geography quizzes here -->
        </div>
    </div>

    <div class="quiz-category">
        <h2>General Knowledge Quizzes</h2>
        <div class="quiz-list">
            <div class="quiz-item"><a href="#">Quiz 1: History</a></div>
            <div class="quiz-item"><a href="#">Quiz 2: Science</a></div>
            <div class="quiz-item"><a href="#">Quiz 3: Pop Culture</a></div>
            <!-- Add more general knowledge quizzes here -->
        </div>
    </div>

    <!-- More categories can be added here -->
</div>

<footer>
    <p>&copy; 2024 Mujeeb's Quizzes | All rights reserved.</p>
</footer>

</body>
</html>
