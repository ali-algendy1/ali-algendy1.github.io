<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VCE Horizon</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
        }
        header {
            background-image: url('https://static.vecteezy.com/system/resources/previews/024/557/298/non_2x/mountain-icon-in-brown-and-white-color-vector.jpg');
            background-size: cover;
            background-position: center;
            color: green;
            padding: 3em 1em;
            text-align: center;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
        }
        header p {
            font-size: 1.2em;
            margin-top: 0.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #2c3e50;
            padding: 1em 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1em;
            font-size: 1em;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #f39c12;
        }
        section {
            max-width: 1000px;
            margin: 2em auto;
            padding: 1em;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            text-align: center;
            margin-bottom: 1em;
            color: #34495e;
        }
        section p {
            line-height: 1.6;
        }
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .feature {
            flex: 1 1 calc(33% - 2em);
            margin: 1em;
            background-color: #ecf0f1;
            padding: 1em;
            border-radius: 8px;
            text-align: center;
        }
        .feature h3 {
            color: #2c3e50;
        }
        footer {
            text-align: center;
            padding: 2em;
            background-color: #2c3e50;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>VCE Horizon</h1>
        <p>Climbing the Mountain to Your Success</p>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#features">Features</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About VCE Horizon</h2>
        <p>At VCE Horizon, we are dedicated to helping students achieve their academic dreams. Our team consists of the top 5% of tutors in Victoria who are passionate about teaching and committed to guiding students to their peak performance. Our personalised approach ensures that every student gets the attention they need to excel.</p>
    </section>
    <section id="features">
        <h2>Why Choose VCE Horizon?</h2>
        <div class="features">
            <div class="feature">
                <h3>Personalised 1:1 Lessons</h3>
                <p>Every lesson is tailored to suit your learning style and academic goals.</p>
            </div>
            <div class="feature">
                <h3>Top 5% Online Tutors</h3>
                <p>Learn from the best tutors in Australia who are experts in their fields.</p>
            </div>
            <div class="feature">
                <h3>Flexible Scheduling</h3>
                <p>Our 24/7 availability ensures that learning fits your schedule.</p>
            </div>
            <div class="feature">
                <h3>Subject Experts</h3>
                <p>Receive guidance from tutors who have excelled in the subjects they teach.</p>
            </div>
            <div class="feature">
                <h3>Qualified Teachers</h3>
                <p>Learn from educators with proven teaching credentials and experience.</p>
            </div>
            <div class="feature">
                <h3>Top Scorers</h3>
                <p>Our tutors have consistently scored in the top percentile of their cohorts.</p>
            </div>
        </div>
    </section>
    <footer id="contact">
        <p>Ready to start your journey? Contact us at <strong>info@vcehorizon.com</strong></p>
        <p>&copy; 2025 VCE Horizon. All rights reserved.</p>
    </footer>
</body>
</html>
