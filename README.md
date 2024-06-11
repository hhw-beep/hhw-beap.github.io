# hhw-beap.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stop Bullying Now</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            font-size: 24px;
        }
        nav {
            background-color: #444;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #555;
        }
        section {
            padding: 20px;
            font-size: 16px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .image {
            display: block;
            margin: 0 auto;
            max-width: 100%; /* Ensure the image does not exceed the container width */
            height: auto;
            padding-bottom: 20px;
        }
        .report-form {
            background-color: #fff;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .report-form input, .report-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .report-form button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 4px;
        }
        .report-form button:hover {
            background-color: #555;
        }

        /* Media Queries for Responsive Design */
        @media (max-width: 600px) {
            header {
                font-size: 20px;
            }
            nav a {
                display: block;
                padding: 10px 0;
            }
            .report-form {
                margin: 10px;
            }
            section {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Stop Bullying Now</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#effects">Effects</a>
        <a href="#prevention">Prevention</a>
        <a href="#support">Support</a>
        <a href="#report">Report Bullying</a>
    </nav>
    <section id="about">
        <h2>About Bullying</h2>
        <p>Bullying is a form of aggressive behavior in which someone intentionally and repeatedly causes another person injury or discomfort. It can take many forms, including physical, verbal, and cyberbullying.</p>
        <img src="bullying_about.png" alt="About Bullying" class="image">
    </section>
    <section id="effects">
        <h2>Effects of Bullying</h2>
        <p>Bullying can have serious consequences for both the victim and the bully. It can lead to depression, anxiety, low self-esteem, and even suicide. It also creates a negative school or work environment.</p>
        <img src="bullying_effects.png" alt="Effects of Bullying" class="image">
    </section>
    <section id="prevention">
        <h2>Bullying Prevention</h2>
        <p>Preventing bullying requires a collective effort from parents, teachers, students, and communities. It's essential to promote empathy, respect, and kindness while providing support for victims and addressing the root causes of bullying behavior.</p>
        <img src="bullying_prevention.png" alt="Bullying Prevention" class="image">
    </section>
    <section id="support">
        <h2>Support for Victims</h2>
        <p>If you or someone you know is being bullied, it's essential to seek support from trusted adults, friends, or helplines. Remember, you're not alone, and there are people who care about you and want to help.</p>
        <img src="bullying_support.jpg" alt="Support for Victims" class="image">
    </section>
    <section id="report">
        <h2>Report Bullying</h2>
        <p>If you or someone you know is being bullied, please report it using the form below. Your report will be confidential and help us take action against bullying.</p>
        <form class="report-form">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="description">Description of the Incident:</label>
            <textarea id="description" name="description" rows="4" required></textarea>
            
            <button type="submit">Submit Report</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Stop Bullying Now - All rights reserved</p>
    </footer>
</body>
</html>
