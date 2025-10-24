<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook Clone</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Login Page -->
    <div id="loginPage" class="page">
        <h1>Welcome to Facebook Clone</h1>
        <input type="text" id="username" placeholder="Enter your username">
        <input type="password" id="password" placeholder="Enter your password">
        <button onclick="login()">Login</button>
    </div>

    <!-- Home Page (Feed) -->
    <div id="homePage" class="page" style="display:none;">
        <h1>News Feed</h1>
        <button onclick="logout()">Logout</button>
        <div id="feed">
            <!-- Posts will go here -->
        </div>
        <textarea id="postContent" placeholder="Write something..."></textarea>
        <button onclick="post()">Post</button>
    </div>

    <!-- Profile Page -->
    <div id="profilePage" class="page" style="display:none;">
        <h1>Profile</h1>
        <button onclick="goToHome()">Back to Home</button>
        <h2 id="profileName">User Profile</h2>
    </div>

    <script src="app.js"></script>
</body>
</html>
