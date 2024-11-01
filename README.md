<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Support Future</title>
    <style>
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}
header {
    background-color: #165b29;
    color: white;
    text-align: center;
    padding: 1rem;
}
nav ul {
    list-style: none;
    padding: 0;
}
nav ul li {
    display: inline;
    margin-right: 1rem;
}
nav ul li a {
    color: white;
    text-decoration: none;
}
section {
    padding: 2rem;
    margin: 1rem 0;
}
.cta-button {
    background-color: #a5d2e2;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}
.impact, .testimonials, .donate {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    text-align: center;
}
.impact div, .testimonials div, .donate div {
    flex: 1 1 30%;
    margin: 10px;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
.impact div img, .testimonials div img {
    max-width: 100%;
    height: auto;
    margin-bottom: 10px;
}
footer {
    background-color: #12db84;
    color: white;
    text-align: center;
    padding: 1rem;
}
nav ul li a:hover {
    text-decoration: underline;
    color: #a5d2e2; 
}

.cta-button:hover {
    background-color: #8bc9d4; 
    transition: background-color 0.3s ease; 
}
    </style>
</head>

<header>
    <h1>Support Future</h1>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="mission.html">Our Mission</a></li>
            <li><a href="involved.html">Get Involved</a></li>
            <li><a href="#impact">Impact</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#donate">Donate</a></li>
        </ul>
    </nav>
</header>

<section id="about">
    <h2>About Our Cause</h2>
    <p>We believe every child deserves access to quality education. Our mission is to provide resources and support to children in need, ensuring they have the opportunity to learn, grow, and achieve their dreams.</p>
</section>

<section id="impact">
    <h2>How Your Donations Help</h2>
    <div class="impact">
        <div>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRrx24SmGdWfIgViYlbpG1aMbADEF3jZvx0ww&s" alt="School Supplies">
            <h3>School Supplies</h3>
            <p>Your donations help provide essential school supplies to children in need.</p>
        </div>
        <div>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR1W9-u9m1yLyQzKnALPfJVKh92An3RtecmJw&s" alt="Scholarships">
            <h3>Scholarships</h3>
            <p>We offer scholarships to underprivileged children to continue their education.</p>
        </div>
        <div>
            <img src="https://media.istockphoto.com/id/1433288447/photo/we-know-the-answer-teacher.jpg?s=612x612&w=0&k=20&c=zy11ys_uUlAoTUKZVc1bTIxomQThKNOuioJWYaszKxA=" alt="Teacher Training" length="300" width="300">
            <h3>Teacher Training</h3>
            <p>Funds are used to train teachers to provide high-quality education.</p>
        </div>
    </div>
</section>

<section id="testimonials">
    <h2>Testimonials</h2>
    <div class="testimonials">
        <div>
            <img src="asha.jpeg" alt="Asha" length="200px" width="250px">
            <p>"Thanks to the scholarship, I can now attend school without worrying about fees."</p>
            <h4>- Asha, Student</h4>
        </div>
        <div>
            <img src="ravi.jpeg" alt="Ravi">
            <p>"The new school supplies have made a huge difference in my child's learning."</p>
            <h4>- Ravi, Parent</h4>
        </div>
        <div>
            <img src="nita.jpeg" alt="Neeta">
            <p>"Teacher training has improved the quality of education in our community."</p>
            <h4>- Neeta, Teacher</h4>
        </div>
    </div>
</section>h

<section id="donate">
    <h2>Make a Donation</h2>
    <p>Your generosity can make a real difference in a child's life. Click the button below to donate now.</p>
    <a href="https://donate.example.com" class="cta-button">Donate Now</a>
</section>

<footer>
    <p>&copy; 2023 Support Child Education. All rights reserved.</p>
</footer>

</body>
</html>
