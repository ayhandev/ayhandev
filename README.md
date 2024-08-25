<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="container">
        <h1 class="animated-heading">👋 Hello, I'm @ayhandev or just Ayhan</h1>
        <p class="slide-in">😄 I am 15 years old (turning 16 soon)</p>
        <p class="slide-in">🙂 I am a web developer, I can write code in HTML, CSS, and a little JS, and my backend is Python.</p>
        <p class="slide-in">👍 Among the frameworks I know Bootstrap, Bulma and Django for the backend.</p>
        <p class="slide-in">Well, I also know how to create telegram bots, but I’m sensitive. So to speak, a hobby 😄</p>
        <p class="slide-in">👀 I am also interested in music, I can play the piano and clarinet, and I go in for sports.</p>
        <p class="slide-in">🌱 Now I'm in 11th grade, I'll graduate from school in a year and want to continue the path of a programmer✌️</p>
        <p class="slide-in">💞️ I can collaborate on web development.</p>
        <p class="slide-in">I will always be happy to help you if you need help, thanks for reading about me😁</p>
    </div>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .fade-in {
            opacity: 0;
            animation: fadeIn 2s forwards;
        }
        @keyframes fadeIn {
            to {
                opacity: 1;
            }
        }
        .slide-in {
            transform: translateX(-100%);
            animation: slideIn 1s forwards;
        }
        @keyframes slideIn {
            to {
                transform: translateX(0);
            }
        }
        h1, h2 {
            color: #333;
        }
        .emoji {
            font-size: 1.5em;
        }
        .animated-heading {
            font-size: 2em;
            color: #333;
            animation: slideUp 2s ease-out;
        }
        @keyframes slideUp {
            0% {
                transform: translateY(50px);
                opacity: 0;
            }
            100% {
                transform: translateY(0);
                opacity: 1;
            }
        }
    </style>
</body>
</html>
