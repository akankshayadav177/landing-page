# landing-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Tracker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Track Your Fitness Goals with Ease</h1>
            <p>Achieve your fitness goals with personalized tracking and insights.</p>
            <a href="#signup" class="cta-button">Start Your Free Trial</a>
        </div>
    </header>

    <section id="features" class="container">
        <h2>Features</h2>
        <div class="feature">
            <img src="workout-icon.png" alt="Workout Tracking">
            <h3>Workout Tracking</h3>
            <p>Track every workout and see your progress over time.</p>
        </div>
        <div class="feature">
            <img src="nutrition-icon.png" alt="Nutrition Tracking">
            <h3>Nutrition Tracking</h3>
            <p>Log your meals and track your calorie intake.</p>
        </div>
        <div class="feature">
            <img src="progress-icon.png" alt="Progress Reports">
            <h3>Progress Reports</h3>
            <p>Get detailed reports of your fitness journey and milestones.</p>
        </div>
    </section>

    <section id="testimonials" class="container">
        <h2>What Our Users Say</h2>
        <div class="testimonial">
            <p>"This app helped me stay on track and motivated throughout my fitness journey!" - Sarah J.</p>
        </div>
        <div class="testimonial">
            <p>"Amazing insights into my workout routine. Highly recommended!" - Michael T.</p>
        </div>
    </section>

    <section id="pricing" class="container">
        <h2>Choose Your Plan</h2>
        <div class="plan">
            <h3>Basic Plan</h3>
            <p>$9.99/month</p>
            <ul>
                <li>Access to workout tracking</li>
                <li>Calorie tracking</li>
            </ul>
            <a href="#signup" class="cta-button">Sign Up</a>
        </div>
        <div class="plan">
            <h3>Premium Plan</h3>
            <p>$19.99/month</p>
            <ul>
                <li>All features in the Basic Plan</li>
                <li>Advanced progress reports</li>
                <li>Personalized fitness plans</li>
            </ul>
            <a href="#signup" class="cta-button">Sign Up</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Fitness Tracker. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
css 
global style
/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
}

/* Header */
header {
    background: #4CAF50;
    color: white;
    text-align: center;
    padding: 50px 0;
}

header h1 {
    font-size: 3em;
}

header p {
    font-size: 1.2em;
    margin-bottom: 20px;
}

.cta-button {
    background-color: #333;
    color: white;
    padding: 15px 30px;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.2em;
}

.cta-button:hover {
    background-color: #555;
}

/* Features Section */
#features {
    text-align: center;
    padding: 40px 0;
}

#features h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.feature {
    display: inline-block;
    width: 30%;
    margin: 20px;
    text-align: center;
}

.feature img {
    width: 80px;
    height: 80px;
    margin-bottom: 15px;
}

.feature h3 {
    font-size: 1.5em;
    margin-bottom: 10px;
}

/* Testimonials Section */
#testimonials {
    background-color: #eee;
    padding: 40px 0;
}

#testimonials h2 {
    font-size: 2.5em;
    text-align: center;
    margin-bottom: 20px;
}

.testimonial {
    text-align: center;
    margin-bottom: 30px;
}

/* Pricing Section */
#pricing {
    padding: 40px 0;
    text-align: center;
}

#pricing h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.plan {
    display: inline-block;
    width: 40%;
    margin: 20px;
    padding: 20px;
    background: white;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.plan h3 {
    font-size: 2em;
    margin-bottom: 15px;
}

.plan ul {
    text-align: left;
    margin-bottom: 20px;
}

.plan ul li {
    margin: 10px 0;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}
