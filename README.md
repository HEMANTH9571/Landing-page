# Landing-page
A landing page of the ninja bikes which is  one of the best web development projects for beginners. This project demands a foundational understanding of HTML and CSS. You will learn how to add columns, divide sections, arrange items, add headers, footers. Most importantly, you will use your creativity to make the page look impressive. The alignments, the padding, the color palette, boxes and all the other elements on the page require attention




html code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ninja Bikes - The true power</title>
    <link rel="stylesheet" href="styles.css">
</head>
<link rel="stylesheet" href="style.css">
<body>

    <header>
      
        <h1>Ninja Bikes</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#models">Models</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Unleash the Power of Ninja Bikes</h1>
            <p>Explore the ultimate in speed, style, and performance.</p>
            <a href="#models" class="cta-button">Browse Our Models</a>
        </div>
    </section>

    <section id="models" class="models">
        <h2>Our Top Models</h2>
        <div class="bike-gallery">
            <div class="bike">
                <img src="Ninja zx 10 r.jpg" alt="Ninja Bike 1">
                <h3>Ninja ZX-10R</h3>
                <p>Performance and precision combined for the ultimate experience.</p>
            </div>
            <div class="bike">
                <img src="ninja 650.jpg" alt="Ninja Bike 2">
                <h3>Ninja 650</h3>
                <p>Unmatched speed, designed for the track.</p>
            </div>
            <div class="bike">
                <img src="ninja 400.jpg" alt="Ninja Bike 3">
                <h3>Ninja 400</h3>
                <p>Perfect balance of power and comfort.</p>
            </div>
        </div>
    </section>

    <footer id="contact">
        <p>Contact Us: <a href="mailto:info@ninjabikes.com">info@ninjabikes.com</a></p>
        <p>Follow Us: <a href="#">Instagram</a> | <a href="#">Facebook</a></p>
    </footer>

</body>
</html>


css code

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

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #333;
  color: #fff;
}

header .logo img {
  width: 120px;
}

nav ul {
  display: flex;
  list-style: none;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #ff6f00;
}

.hero {
  background: url('background image.jpg') no-repeat center center/cover;
  height: 70vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
}

.hero-content h1 {
  font-size: 3rem;
  margin-bottom: 20px;
}

.hero-content p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.cta-button {
  padding: 10px 20px;
  background-color: #ff6f00;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-size: 1rem;
}

.cta-button:hover {
  background-color: #e65c00;
}

.models {
  padding: 40px 20px;
  text-align: center;
  background-color: #fff;
}

.models h2 {
  font-size: 2.5rem;
  margin-bottom: 30px;
}

.bike-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

.bike {
  background: #fff;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.bike img {
  width: 100%;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.bike h3 {
  font-size: 1.8rem;
  margin-top: 20px;
}

.bike p {
  font-size: 1rem;
  color: #555;
}

footer {
  padding: 20px;
  text-align: center;
  background-color: #333;
  color: white;
}

footer a {
  color: #ff6f00;
  text-decoration: none;
}

footer a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .hero-content h1 {
      font-size: 2.5rem;
  }

  .cta-button {
      padding: 8px 16px;
  }

  .bike-gallery {
      grid-template-columns: 1fr;
  }
}

@media (max-width: 480px) {
  .hero-content h1 {
      font-size: 2rem;
  }

  .cta-button {
      padding: 6px 12px;
  }
}


![Screenshot 2024-12-08 211612](https://github.com/user-attachments/assets/7912f384-80fe-4254-84ae-9755a71e4269)

![Screenshot 2024-12-08 211637](https://github.com/user-attachments/assets/84407390-36c0-48bc-8f64-f4490f715766)
