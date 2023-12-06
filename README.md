<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
<foreignObject width="100" height="100">
    <div xmlns="http://www.w3.org/1999/xhtml">
        <!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Awesome Profile</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
    }

    #profile {
      background-color: #161b22;
      border-radius: 10px;
      padding: 20px;
      width: 400px;
      animation: fadeIn 1s ease-in-out;
    }

    img {
      border-radius: 50%;
      margin-bottom: 20px;
      animation: rotate 2s linear infinite;
    }

    h1 {
      color: #58a6ff;
      animation: colorChange 2s infinite alternate;
    }

    p {
      margin-bottom: 20px;
      animation: slideIn 1s ease-in-out;
    }

    a {
      text-decoration: none;
      color: #58a6ff;
    }

    .badge {
      display: inline-block;
      padding: 5px 10px;
      margin: 0 5px;
      border-radius: 5px;
      background-color: #58a6ff;
      color: #0d1117;
    }

    .game {
      background-color: #1f6feb;
      color: #0d1117;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease-in-out;
    }

    .game:hover {
      background-color: #0d6efd;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    @keyframes rotate {
      to {
        transform: rotate(360deg);
      }
    }

    @keyframes colorChange {
      to {
        color: #79b8ff;
      }
    }

    @keyframes slideIn {
      from {
        transform: translateY(-20px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }
  </style>
</head>

<body>
  <div id="profile">
    <img src="your-profile-image-url" width="100" height="100" alt="Your Name">
    <h1>Your Name</h1>
    <p>Passionate Developer 🚀 | Open Source Enthusiast 🌐 | Avid Reader 🚀</p>

    <h2>About Me</h2>
    <p>I'm currently working on <strong>Your Current Project</strong> and learning <strong>What You're Learning</strong>. I'm looking to collaborate on <strong>Open Source Projects</strong> and seeking help with <strong>What You Need Help With</strong>.</p>

    <h2>Skills</h2>
    <p>Languages: JavaScript, Python, Java</p>
    <p>Frameworks: React, Node.js, Flask</p>
    <p>Database: MongoDB, MySQL</p>
    <p>Tools: Git, VS Code, Docker</p>

    <h2>GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=your-username&show_icons=true&count_private=true&theme=dark"
      alt="GitHub Stats">

    <h2>Connect with Me</h2>
    <a href="https://www.linkedin.com/in/your-linkedin-profile/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
    <a href="https://twitter.com/your-twitter-handle" target="_blank" rel="noopener noreferrer">Twitter</a>
    <a href="https://your-portfolio-website.com" target="_blank" rel="noopener noreferrer">Portfolio</a>

    <h2>Let's Play a Game</h2>
    <div class="game" onclick="playGame()">Click to Play a Game with Me</div>
    <p id="game-result"></p>

    <h2>Latest Blog Posts</h2>
    <a href="#" target="_blank" rel="noopener noreferrer">Blog Post 1</a><br>
    <a href="#" target="_blank" rel="noopener noreferrer">Blog Post 2</a><br>
    <a href="#" target="_blank" rel="noopener noreferrer">Blog Post 3</a>
  </div>

  <script>
    function playGame() {
      const numberToGuess = Math.floor(Math.random() * 10) + 1;
      const userGuess = prompt("Guess the number between 1 and 10:");
      const result = userGuess == numberToGuess ? "Congratulations! You guessed it right!" : `Oops! The correct number was ${numberToGuess}. Try again!`;
      document.getElementById("game-result").innerText = result;
    }
  </script>
</body>

</html>

        <!-- Other embed HTML element/text into SVG -->
    </div>
</foreignObject>
</svg>
