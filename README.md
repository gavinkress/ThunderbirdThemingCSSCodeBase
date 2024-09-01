<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thunderbird Custom CSS Repository</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(120deg, #0A74DA, #FFFFFF);
            color: #fff;
            text-align: center;
            overflow-x: hidden;
        }
        .header {
            padding: 50px;
            background: rgba(10, 116, 218, 0.8);
            animation: backgroundAnim 10s infinite alternate;
        }
        .header h1 {
            margin: 0;
            font-size: 3em;
            animation: fadeIn 2s ease-in-out;
        }
        .header p {
            margin: 0;
            font-size: 1.2em;
            animation: fadeIn 3s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes backgroundAnim {
            from { background-color: #0A74DA; }
            to { background-color: #ffffff; color: #0A74DA; }
        }
        .content {
            padding: 30px;
        }
        .content h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        .content p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }
        .button {
            padding: 10px 20px;
            background-color: #00a57c;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #007b5e;
        }
        .footer {
            padding: 20px;
            background: #131313;
        }
        .footer a {
            color: #00a57c;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Welcome to the Thunderbird Custom CSS Repository!</h1>
        <p>Share, Collaborate, and Customize Thunderbird's Appearance with Ease.</p>
    </div>
    <div class="content">
        <h2>About</h2>
        <p>This repository is dedicated to sharing custom CSS snippets that can enhance the Thunderbird experience. Whether you're looking to tweak colors, add new features, or create an entirely new theme, this is the place to start.</p>
        <button class="button">Get Started</button>
    </div>
    <div class="footer">
        <p>Contribute on <a href="https://github.com/your-profile">GitHub</a> | Join the Discussion on <a href="#">Forums</a></p>
    </div>
</body>
</html>
