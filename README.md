# Sesoblade.github.io
Webpage

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #444;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
    }
    main {
      padding: 20px;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
  <main>
    <section id="home">
      <h2>Home</h2>
      <p>This is the home section of my website.</p>
    </section>
    <section id="about">
      <h2>About</h2>
      <p>Learn more about me and my website here.</p>
    </section>
    <section id="contact">
      <h2>Contact</h2>
      <p>Get in touch with me!</p>
    </section>
  </main>
  <footer>
    <p>&copy; 2023 Your Website. All rights reserved.</p>
  </footer>
</body>
</html>
Run HTML
How to Use This Code:
Copy the code above.

Save it as index.html.

Open it in your browser to see your website.

Let me know if you want to add more features (e.g., JavaScript, animations, or a contact form)! 🚀

Responsive website that I can use to sell my art work
Got it! Let’s create a responsive website for selling your artwork. I’ll include a clean design, a gallery for your art, and a contact form for potential buyers. Here's the code:

Code: Responsive Art Portfolio Website
html
Copy
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Art Portfolio</title>
  <style>
    /* General Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    a {
      text-decoration: none;
      color: #333;
    }
    a:hover {
      color: #555;
    }

    /* Header */
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    /* Navigation */
    nav {
      background-color: #444;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      font-size: 1.1rem;
    }

    /* Gallery Section */
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .gallery img {
      width: 100%;
      max-width: 300px;
      margin: 10px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }

    /* Contact Form */
    .contact {
      padding: 20px;
      background-color: #fff;
      margin: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .contact h2 {
      text-align: center;
    }
    .contact form {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .contact input, .contact textarea {
      width: 80%;
      max-width: 500px;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contact button {
      padding: 10px 20px;
      background-color: #333;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .contact button:hover {
      background-color: #555;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }
      nav a {
        font-size: 1rem;
      }
      .gallery img {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Your Art Portfolio</h1>
    <p>Showcasing Beautiful Creations</p>
  </header>
  <nav>
    <a href="#gallery">Gallery</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
  <main>
    <!-- Gallery Section -->
    <section id="gallery" class="gallery">
      <img src="https://via.placeholder.com/300" alt="Artwork 1">
      <img src="https://via.placeholder.com/300" alt="Artwork 2">
      <img src="https://via.placeholder.com/300" alt="Artwork 3">
      <img src="https://via.placeholder.com/300" alt="Artwork 4">
      <img src="https://via.placeholder.com/300" alt="Artwork 5">
      <img src="https://via.placeholder.com/300" alt="Artwork 6">
    </section>

    <!-- About Section -->
    <section id="about" style="padding: 20px;">
      <h2>About Me</h2>
      <p>Welcome to my art portfolio! I specialize in creating unique and inspiring pieces that reflect my passion for creativity. Feel free to explore my gallery and reach out if you'd like to purchase or commission a piece.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
      <h2>Contact Me</h2>
      <form action="#" method="post">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>
  <footer>
    <p>&copy; 2023 Your Art Portfolio. All rights reserved.</p>
  </footer>
</body>
</html>
