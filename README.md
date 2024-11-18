my-website/
├── index.html
├── styles.css
└── script.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 id="greeting">Welcome to My Website!</h1>
    <button onclick="changeGreeting()">Change Greeting</button>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin-top: 50px;
}

h1 {
    color: #333;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}
function changeGreeting() {
    const greetingElement = document.getElementById('greeting');
    greetingElement.textContent = 'Hello, World!';
}
git clone https://github.com/YOUR_USERNAME/my-website.git
git add .
git commit -m "Initial commit"
git push origin main
