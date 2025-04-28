<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Awesome Services</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: #f9f9f9; color: #333; }
    header {
      background: linear-gradient(90deg, #0077ff, #00c3ff);
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #003366;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }
    nav a:hover {
      background: #0055aa;
      border-radius: 5px;
    }
    .hero {
      background: url('https://images.pexels.com/photos/3184465/pexels-photo-3184465.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940') no-repeat center center/cover;
      height: 500px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      background: rgba(0, 0, 0, 0.5);
      padding: 1rem;
      border-radius: 10px;
    }
    .container {
      padding: 4rem 2rem;
      max-width: 1200px;
      margin: auto;
    }
    .services, .testimonials, .contact-form {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }
    .service-card, .testimonial-card {
      background: white;
      flex: 1 1 300px;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.3s;
    }
    .service-card:hover, .testimonial-card:hover {
      transform: translateY(-10px);
    }
    .service-card img, .testimonial-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .service-card h3, .testimonial-card h3 {
      padding: 1rem;
      color: #0077ff;
    }
    .service-card p, .testimonial-card p {
      padding: 0 1rem 1.5rem;
    }
    footer {
      background: #003366;
      color: white;
      text-align: center;
      padding: 2rem;
      margin-top: 2rem;
    }
    form {
      background: white;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      flex: 1 1 500px;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.8rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      background: #0077ff;
      color: white;
      padding: 1rem 2rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
    }
    form button:hover {
      background: #0055aa;
    }
    @media (max-width: 768px) {
      .hero h1 { font-size: 2rem; }
    }
  </style>
</head>
<body>

<header>
  <h1>Awesome Services</h1>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">Services</a>
  <a href="#">Testimonials</a>
  <a href="#">Contact</a>
</nav>

<section class="hero">
  <h1>Your Success, Our Mission</h1>
</section>

<section class="container">
  <h2 style="text-align:center; margin-bottom:2rem;">Our Services</h2>
  <div class="services">

    <div class="service-card">
      <img src="https://images.pexels.com/photos/1181671/pexels-photo-1181671.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Cloud Hosting">
      <h3>Cloud Hosting</h3>
      <p>Reliable and secure cloud hosting to keep your business always online.</p>
    </div>

    <div class="service-card">
      <img src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Web Development">
      <h3>Web Development</h3>
      <p>Creative and responsive websites tailored for your brand success.</p>
    </div>

    <div class="service-card">
      <img src="https://images.pexels.com/photos/3183150/pexels-photo-3183150.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="SEO Optimization">
      <h3>SEO Optimization</h3>
      <p>Maximize your visibility and reach a wider audience online easily.</p>
    </div>

    <div class="service-card">
      <img src="https://images.pexels.com/photos/4050288/pexels-photo-4050288.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Mobile Apps">
      <h3>Mobile App Development</h3>
      <p>Beautiful Android and iOS apps developed by our experienced teams.</p>
    </div>

  </div>
</section>

<section class="container">
  <h2 style="text-align:center; margin-bottom:2rem;">What Our Clients Say</h2>
  <div class="testimonials">

    <div class="testimonial-card">
      <img src="https://images.pexels.com/photos/774909/pexels-photo-774909.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Client 1">
      <h3>Sarah Johnson</h3>
      <p>"Absolutely professional! My website is now faster and more beautiful than ever."</p>
    </div>

    <div class="testimonial-card">
      <img src="https://images.pexels.com/photos/220453/pexels-photo-220453.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Client 2">
      <h3>Michael Lee</h3>
      <p>"The team helped my business grow online massively with their SEO skills."</p>
    </div>

    <div class="testimonial-card">
      <img src="https://images.pexels.com/photos/712521/pexels-photo-712521.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Client 3">
      <h3>Emily Carter</h3>
      <p>"Loved working with them! My new app is sleek, fast and easy to use."</p>
    </div>

  </div>
</section>

<section class="container">
  <h2 style="text-align:center; margin-bottom:2rem;">Contact Us</h2>
  <div class="contact-form">
    <form action="#" method="post">
      <input type="text" name="name" placeholder="Your Full Name" required>
      <input type="email" name="email" placeholder="Your Email Address" required>
      <input type="text" name="subject" placeholder="Subject" required>
      <textarea name="message" rows="5" placeholder="Write your message here..." required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>
</section>

<footer>
  <p>MADE BY MUBASHIR</p>
</footer>

</body>
</html>
