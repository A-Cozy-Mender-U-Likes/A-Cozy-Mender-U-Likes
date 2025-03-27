<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Hockey Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0a192f;
            color: white;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: black;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 32px;
            font-weight: bold;
        }
        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background: navy;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.2);
            text-align: center;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .section {
            background: black;
            color: white;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
            flex: 1 1 calc(45% - 20px);
            text-align: center;
        }
        footer {
            background: black;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
            font-size: 16px;
        }
        .nav {
            display: flex;
            justify-content: center;
            background: black;
            padding: 10px;
        }
        .nav a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            margin: 0 10px;
            border-radius: 5px;
            background: navy;
        }
        .nav a:hover {
            background: white;
            color: black;
        }
    </style>
</head>
<body>
    <header>My Hockey Website</header>
    <nav class="nav">
        <a href="#about">About</a>
        <a href="#history">History</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <h1>Welcome</h1>
        <p>This is a template. Customize it with your own content!</p>
        <div class="content">
            <div class="section" id="about">
                <h2>About Me</h2>
                <p>Write a short introduction about yourself and your love for hockey.</p>
            </div>
            <div class="section" id="history">
                <h2>Hockey History</h2>
                <p>Add interesting historical facts about hockey.</p>
            </div>
            <div class="section" id="gallery">
                <h2>Photo Gallery</h2>
                <p>Insert images or links to your favorite hockey moments.</p>
            </div>
            <div class="section" id="contact">
                <h2>Contact Me</h2>
                <p>Provide contact details or links to your social media.</p>
            </div>
        </div>
    </div>
    <footer>&copy; 2025 My Hockey Website. Customize as needed.</footer>
</body>
</html>
