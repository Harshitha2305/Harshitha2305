<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechTalk 1.O - Rajarajeswari College of Engineering</title>
    <style>
        body { 
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        nav {
            background-color: #333;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #ddd;
            color: black;
        }

        .container {
            padding: 20px;
            max-width: 1100px;
            margin: 0 auto;
        }

        .hero {
            text-align: center;
            background-color: #2196F3;
            color: white;
            padding: 60px 20px;
        }

        .hero h1 {
            font-size: 3em;
        }

        .section {
            margin: 40px 0;
        }

        .section h2 {
            color: #333;
            font-size: 2em;
        }

        .section p {
            font-size: 1.2em;
        }

        .share-btns {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .share-btns a {
            padding: 10px 20px;
            text-decoration: none;
            color: white;
            border-radius: 5px;
            font-weight: bold;
        }

        .share-btns .whatsapp {
            background-color: #25D366;
        }

        .share-btns .facebook {
            background-color: #3b5998;
        }

        .share-btns .twitter {
            background-color: #1DA1F2;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Welcome to TechTalk 1.O!</h1>
        <p>An Exciting Hackathon by Rajarajeswari College of Engineering</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#prizes">Prizes</a>
        <a href="#register">Register</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <h1>TechTalk 1.O</h1>
        <p>Join us for an exciting hackathon filled with innovation, collaboration, and amazing cash prizes!</p>
    </div>

    <div class="container">

        <section id="about" class="section">
            <h2>About the Event</h2>
            <p>TechTalk 1.O is a dynamic 24-hour hackathon where participants will work in teams to solve real-world challenges through innovative software and hardware solutions. Hosted by Rajarajeswari College of Engineering, this event is open to all enthusiastic coders, designers, and innovators!</p>
        </section>

        <section id="prizes" class="section">
            <h2>Exciting Cash Prizes!</h2>
            <p>Participate and compete for cash prizes worth up to ₹10,000! Showcase your skills and walk away with more than just experience.</p>
            <ul>
                <li><strong>1st Prize:</strong> ₹10,000</li>
                <li><strong>2nd Prize:</strong> ₹7,500</li>
                <li><strong>3rd Prize:</strong> ₹5,000</li>
            </ul>
        </section>

        <section id="register" class="section">
            <h2>Register Now!</h2>
            <p>Don't miss out on this opportunity! Register your team and secure your spot for TechTalk 1.0.</p>
            <a href="registration_form_link" style="color: #2196F3; font-weight: bold;">Click here to register</a>
        </section>

        <!-- Share the Event Section -->
        <section id="share" class="section">
            <h2>Share the Event</h2>
            <p>Invite your friends to join the hackathon!</p>
            <div class="share-btns">
                <a href="https://api.whatsapp.com/send?text=Check%20out%20TechTalk%201.0%20Hackathon%20at%20Rajarajeswari%20College%20of%20Engineering!%20Visit:%20[YourWebsiteURL]"
                    class="whatsapp" target="_blank">Share on WhatsApp</a>
                <a href="https://www.facebook.com/sharer/sharer.php?u=[YourWebsiteURL]" class="facebook" target="_blank">Share on Facebook</a>
                <a href="https://twitter.com/intent/tweet?text=Join%20TechTalk%201.0%20Hackathon!%20Visit:%20[YourWebsiteURL]"
                    class="twitter" target="_blank">Share on Twitter</a>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Contact Us</h2>
            <p>For any queries, feel free to reach out:</p>
            <p><b>Email:</b><a href=ignitorsspark@gmail.com style="color: #2196F3; font-weight: bold;">ignitorsspark@gmail.com</a></p>
            <p><strong>Phone:</strong> +91-9876543210</p>
        </section>

    </div>

    <footer>
        <p>&copy; 2024 Rajarajeswari College of Engineering | TechTalk 1.0</p>
    </footer>

</body>

</html>
