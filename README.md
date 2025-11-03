<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CRMS Cyber Eagles FTC Team</title>
<style>
  :root {
    --blue: #004aad;
    --gold: #ffcc00;
    --dark: #0b0b0b;
    --light: #f9f9f9;
  }

  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body {
    font-family: "Poppins", sans-serif;
    background: var(--light);
    color: #222;
    line-height: 1.6;
  }

  header {
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1581093588401-22cd7f2a9b6d') center/cover no-repeat;
    color: white;
    text-align: center;
    padding: 6rem 1rem 4rem;
  }

  header h1 {
    font-size: 3rem;
    letter-spacing: 2px;
  }

  nav {
    display: flex;
    justify-content: center;
    background: var(--blue);
    flex-wrap: wrap;
  }

  nav a {
    color: white;
    text-decoration: none;
    padding: 1rem 1.5rem;
    font-weight: 500;
    transition: background 0.3s;
  }

  nav a:hover {
    background: var(--gold);
    color: var(--dark);
  }

  section {
    padding: 4rem 2rem;
    max-width: 1000px;
    margin: auto;
  }

  h2 {
    color: var(--blue);
    font-size: 2.2rem;
    text-align: center;
    margin-bottom: 1.5rem;
  }

  .about {
    text-align: center;
  }

  .about p {
    max-width: 750px;
    margin: 0 auto;
  }

  .team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.5rem;
    margin-top: 2rem;
  }

  .card {
    background: white;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    padding: 1.5rem;
    text-align: center;
    transition: transform 0.2s ease;
  }

  .card:hover {
    transform: translateY(-5px);
  }

  .sponsors {
    background: var(--blue);
    color: white;
    text-align: center;
    padding: 5rem 2rem;
  }

  .sponsors h2 {
    color: var(--gold);
  }

  .sponsor-logos {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 2rem;
    margin-top: 2rem;
  }

  .sponsor-logos img {
    max-width: 200px;
    height: auto;
    filter: drop-shadow(0 3px 6px rgba(0,0,0,0.2));
    background: white;
    border-radius: 8px;
    padding: 10px;
  }

  footer {
    background: var(--dark);
    color: #ccc;
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
  }

  @media (max-width: 600px) {
    header h1 { font-size: 2.2rem; }
    nav a { padding: 0.8rem; }
  }
</style>
</head>
<body>

<header>
  <h1>CRMS Cyber Eagles FTC Team #XXXX</h1>
  <p>Canyon Ridge Middle School • Inspiring STEM Innovation</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#team">Our Team</a>
  <a href="#hardware">Hardware</a>
  <a href="#software">Software</a>
  <a href="#marketing">Marketing</a>
  <a href="#sponsors">Sponsors</a>
</nav>

<section id="about" class="about">
  <h2>About Us</h2>
  <p>
    The CRMS Cyber Eagles are a passionate FIRST Tech Challenge team from Canyon Ridge Middle School. 
    We combine creativity, coding, and engineering to design competitive robots while learning teamwork, leadership, and real-world problem solving.
  </p>
</section>

<section id="team">
  <h2>Meet Our Team</h2>
  <div class="team-grid">
    <div class="card">
      <h3>Team Captain</h3>
      <p>Leads design and strategy while keeping everyone motivated and organized.</p>
    </div>
    <div class="card">
      <h3>Software Lead</h3>
      <p>Programs the robot using Java, mastering autonomous routines and sensors.</p>
    </div>
    <div class="card">
      <h3>Hardware Lead</h3>
      <p>Designs, builds, and maintains the robot’s mechanical systems.</p>
    </div>
    <div class="card">
      <h3>Marketing & Outreach</h3>
      <p>Builds connections with the community and manages our social presence.</p>
    </div>
  </div>
</section>

<section id="hardware">
  <h2>Hardware</h2>
  <p>
    Our robot features custom-designed components built for precision, durability, and performance. 
    Using CAD modeling and modular structures, we optimize every part for the season’s unique challenges.
  </p>
</section>

<section id="software">
  <h2>Software</h2>
  <p>
    We program our robots using the FTC SDK with Java, integrating Road Runner for motion planning and 
    advanced sensor feedback for accurate autonomous control.
  </p>
</section>

<section id="marketing">
  <h2>Marketing</h2>
  <p>
    We showcase our engineering journey through social media, community events, and presentations to sponsors. 
    Our team values professionalism and outreach as much as engineering excellence.
  </p>
</section>

<section id="sponsors" class="sponsors">
  <h2>We Love Our Sponsors!</h2>
  <div class="sponsor-logos">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/25/One_Hour_Air_Conditioning_%26_Heating_logo.png" alt="One Hour Air Conditioning & Heating">
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/ab/First_Tech_Challenge_logo.svg" alt="FIRST Tech Challenge">
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/FTC_logo.png" alt="FTC Logo">
  </div>
</section>

<footer>
  © 2025 CRMS Cyber Eagles FTC Team • Canyon Ridge Middle School • Built with ❤️ by the team
</footer>

</body>
</html>
