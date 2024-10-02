<!DOCTYPE html>
<html xmlns:th="http://www.thymeleaf.org">
<head>
    <title>Counseling Services</title>
    <link rel="stylesheet" href="/css/style.css"/>
</head>
<body>
    <header>
        <h1>Counseling Services</h1>
        <nav>
            <a href="/">Home</a>
            <a href="/resources">Resources</a>
            <a href="/forum">Community Forum</a>
            <a href="/crisis">Crisis Help</a>
        </nav>
    </header>
    
    <section>
        <h2>Available Therapists</h2>
        <ul>
            <li>Dr. Alice Johnson (Psychologist) - <a href="/schedule?id=1">Schedule Session</a></li>
            <li>Dr. Mark Stevens (Counselor) - <a href="/schedule?id=2">Schedule Session</a></li>
            <!-- Dynamically populate more therapists -->
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 Mental Health Support Platform</p>
    </footer>
</body>
</html>
