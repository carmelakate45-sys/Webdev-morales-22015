<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Professional Profile</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="profile-header">
        <img src="https://pin.it/3mhON9H91" alt="https://pin.it/9ar3NjTeC" class="https://pin.it/3mhON9H91">
        <h1>Carmela kate morales</h1>
        <p class="tagline">yoyoy</p>
    </header>

    <main class="profile-main">
        <section class="about">
            <h2>👋 About Me</h2>
            <p>I'm a student with nothing  years of experience, passionate about being rich. I thrive on being rich.</p>
        </section>

        <section class="skills">
            <h2>🛠️ Skills</h2>
            <ul class="skills-list">
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                
                
            </ul>
        </section>

        <section class="contact">
            <h2>✉️ Contact</h2>
            <p>Email: <a href="mailto:youremail@example.com</a></p>
            <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></p>
            <p>GitHub: <a href="https://github.com/yourusername" target="_blank">carmelakate45</a></p>
        </section>
    </main>

    <footer class="profile-footer">
        <p>&copy; 2025 kate. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f7f6; /* Light gray background */
    color: #333;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

.profile-main {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #ffffff; /* White card background */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

h1, h2 {
    color: #2c3e50; /* Dark blue heading color */
}

a {
    color: #3498db; /* Blue link color */
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* --- Header Section --- */
.profile-header {
    background-color: #3498db; /* Blue header background */
    color: white;
    padding: 40px 20px;
    text-align: center;
    border-radius: 8px 8px 0 0; /* Match main content radius */
    margin-bottom: 20px;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%; /* Makes the image circular */
    border: 5px solid white;
    object-fit: cover;
    margin-bottom: 15px;
}

.tagline {
    font-style: italic;
    opacity: 0.9;
}

/* --- Main Content Sections --- */
section {
    padding: 20px 0;
    border-bottom: 1px solid #e0e0e0;
}

section:last-child {
    border-bottom: none;
}

.skills-list {
    list-style-type: none;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.skills-list li {
    background-color: #eaf2f8; /* Light blue skill tag background */
    color: #2c3e50;
    padding: 5px 15px;
    border-radius: 20px;
    font-size: 0.9em;
    font-weight: bold;
}

/* --- Footer Section --- */
.profile-footer {
    text-align: center;
    padding: 15px;
    font-size: 0.8em;
    color: #999;
    margin-top: 20px;
}