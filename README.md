<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Welcome to Pawan's Website</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f0f8ff;
    }

    header {
      background-color: #333;
      color: white;
      padding: 1rem;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background-color: #444;
      padding: 0.8rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: yellow;
    }

    .container {
      padding: 30px;
      text-align: center;
    }

    .gallery img {
      width: 200px;
      height: 150px;
      margin: 10px;
      border-radius: 10px;
      border: 2px solid #ccc;
      transition: transform 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
      border-color: #333;
    }

    form {
      margin-top: 30px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    input, textarea {
      width: 300px;
      padding: 10px;
      margin: 10px;
      border: 1px solid #888;
      border-radius: 5px;
    }

    button {
      padding: 10px 20px;
      background: #333;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background: darkgreen;
    }

    footer {
      background-color: #222;
      color: #bbb;
      text-align: center;
      padding: 1rem;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Pawan Puri's Website 🚀</h1>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container" id="home">
    <h2>Hello, I am Pawan Puri!</h2>
    <p>I’m learning HTML, Tally, and Spoken English. This is my first live website using GitHub Pages. 😄</p>
  </div>

  <div class="container" id="gallery">
    <h2>My Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/200x150?text=Image+1" alt="Image 1" />
      <img src="https://via.placeholder.com/200x150?text=Image+2" alt="Image 2" />
      <img src="https://via.placeholder.com/200x150?text=Image+3" alt="Image 3" />
    </div>
  </div>

  <div class="container" id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>

  <footer>
    © 2025 Pawan Puri. All rights reserved.
  </footer>

</body>
</html>
