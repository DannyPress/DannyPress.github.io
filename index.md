<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daniel Pressler</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding-top: 60px; /* Height of the fixed header */
        }
        .header {
            background-color: #333;
            color: white;
            position: fixed;
            top: 0;
            width: 100%;
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 60px;
            z-index: 1000;
        }
        .header a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        .header a:hover {
            background-color: #575757;
        }
        section {
            padding: 20px;
            margin: 10px 0;
        }
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

<div class="header">
    <a href="#about">About Me</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#career">Career Objectives</a>
    <a href="#hobbies">Hobbies</a>
    <a href="#contact">Contact</a>
</div>

<section id="about">
    <h2>About Me</h2>
    <p>My name is Daniel Pressler, typically go by Danny. I am a current junior at Lehigh University double majoring in finance and business information systems, while also minoring in computer science. This upcoming summer I plan on interning at <a href="https://fsinvestments.com/">FS Investments</a> on their portfolio operations team. If you have any questions, feel free to reach out to me via email or phone found on my <a href="https://docs.google.com/document/d/1OZFo_MYryiSrIePP2O6gl_asl9wdEXH1Pt8VXRazSj0/edit?usp=sharing">Resume</a> or at the bottom of the page.</p>
    <img src="images/profile.jpg" alt="Profile Image">
</section>

<section id="portfolio">
    <h2>Portfolio</h2>
    <h3>Projects</h3>
    <p>Here are some of my projects that I have developed in my life inside and outside of academia:</p>
    <h4><a href="https://wealth-advisor-dashboard-zxeuck5wssug23mf7cjon.streamlit.app/">Wealth Management Dashboard Project</a></h4>
    <img src="images/wealth_dashboard.png" alt="Wealth Management Dashboard">
    <h4><a href="https://docs.google.com/document/d/10cHpVjkIyesi2v7P9vyu_-CrYbkO752d7X_vC23LTtU/edit?usp=sharing">A Finance Project I Worked on in a Systems Class (BIS 311)</a></h4>
    <img src="images/project_screenshot.png" alt="Project Screenshot">
</section>

<section id="career">
    <h2>Career Objectives</h2>
    <p>For my longer-term career path I plan on taking the CFA exams and to acquire the charter sometime in the future and work in portfolio management.</p>
</section>

<section id="hobbies">
    <h2>Hobbies</h2>
    <ul>
        <li>Snowboarding</li>
        <li>CrossFit</li>
        <li>Practicing Mandarin</li>
        <li>Playing the piano</li>
        <li>Participating in lacrosse</li>
        <li>Cheering for the New York Giants</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact Information</h2>
    <p><strong>Personal Email:</strong> dpressler1@gmail.com</p>
    <p><strong>School Email:</strong> dbp225@lehigh.edu</p>
    <p><strong>Phone Number:</strong> 732-666-2331</p>
</section>

</body>
</html>
