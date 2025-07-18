<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AuraSpaces Interiors</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: #fafafa;
      color: #333;
    }
    header {
      background: url('https://images.unsplash.com/photo-1505693416388-ac5ce068fe85') center/cover no-repeat;
      padding: 5rem 2rem;
      text-align: center;
      color: white;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
    }
    header p {
      font-size: 1.2rem;
    }
    nav {
      background-color: #222;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 1rem;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      text-align: center;
      font-family: 'Playfair Display', serif;
    }
    .gallery, .features, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .gallery img, .projects img {
      width: 100%;
      border-radius: 10px;
    }
    .feature-box {
      background: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      text-align: center;
    }
    .feature-box h3 {
      margin-top: 0;
    }
    .contact {
      background: #f4f4f4;
      padding: 2rem;
      border-radius: 10px;
    }
    .contact form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    .contact input, .contact textarea {
      padding: 0.75rem;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 1rem;
    }
    .contact button {
      padding: 0.75rem;
      background-color: #222;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #222;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <h1>AuraSpaces Interiors</h1>
    <p>Elegant & Functional Interior Designs Tailored Just for You</p>
  </header>
  <nav>
    <a href="#features">Why Us</a>
    <a href="#projects">Past Work</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="features">
    <h2>Why Choose AuraSpaces?</h2>
    <div class="features">
      <div class="feature-box">
        <h3>End-to-End Solutions</h3>
        <p>From layout planning to execution, we handle everything professionally.</p>
      </div>
      <div class="feature-box">
        <h3>Experienced Designers</h3>
        <p>Our experts bring over 10 years of creative excellence to your space.</p>
      </div>
      <div class="feature-box">
        <h3>Budget Friendly</h3>
        <p>We make sure style and function stay affordable without compromise.</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Past Projects</h2>
    <div class="projects">
      <div>
        <img src="https://images.unsplash.com/photo-1588854337112-2b87f8d0fb3d" alt="Living Room">
        <p>Modern 3BHK Living Room</p>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c" alt="Kitchen">
        <p>Contemporary Modular Kitchen</p>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1589652717521-10c0d092dea9" alt="Bedroom">
        <p>Elegant Master Bedroom</p>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1588852958631-6881c1c5cf62" alt="Workstation">
        <p>Home Office Setup</p>
      </div>
    </div>
  </section>

  <section id="gallery">
    <h2>Gallery of Designs</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1615874959474-d609969a7ee0" alt="Accent wall">
      <img src="https://images.unsplash.com/photo-1598300057351-70c6030c5be7" alt="Earth tones">
      <img src="https://images.unsplash.com/photo-1616486490847-5ac61ae0c343" alt="Bathroom design">
      <img src="https://images.unsplash.com/photo-1584941211330-7ac70e38da47" alt="Grey gold">
      <img src="https://images.unsplash.com/photo-1627308595229-7830a5c91f9f" alt="Kids room">
      <img src="https://images.unsplash.com/photo-1632156631038-597da44a9a50" alt="Dining area">
    </div>
  </section>

  <section id="contact">
    <h2>Get In Touch</h2>
    <div class="contact">
      <form>
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <textarea placeholder="Your Message" rows="5" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 AuraSpaces Interiors | Designed with passion.</p>
  </footer>
</body>
</html>
