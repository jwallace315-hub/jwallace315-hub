<link href="https://fonts.googleapis.com/css2?family=Jost:wght@300;400;600&display=swap" rel="stylesheet">

<!-- ================== STYLES ================== -->
<style>
body {
  margin: 0;
  font-family: 'Jost', Arial, sans-serif;
  scroll-behavior: smooth;
  background-color: #fffdf7
}

/* Navbar */
.navbar {
  position: sticky;
  top: 0;
  background-color: #111;
  color: white;
  padding: 15px 30px;
  font-size: 20px;
  font-weight: bold;
  z-index: 1000;
}

/* Section layout */
.section {
  padding: 80px 20px;
  max-width: 900px;
  margin: auto;
}

.section h2 {
  text-align: center;
  margin-bottom: 20px;
}

/* Content boxes */
.box {
  background-color: #f4f4f4;
  padding: 20px;
  border-radius: 8px;
}

/* Split layouts */
.split-3 {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 15px;
}

.split-2 {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
}

/* Contact */
.contact p {
  text-align: center;
  font-size: 18px;
}
</style>

<!-- ================== NAVBAR ================== -->
<div class="navbar">
  GurNFriends
</div>

<!-- ================== WHAT WE DO ================== -->
<div class="section">
  <h2>What it is we do</h2>
  <div class="box">
    <p>
      We provide professional game user research services designed to help developers
      understand player behavior, improve usability, and create better player experiences.
      Our insights turn player feedback into actionable design improvements.
    </p>
  </div>
</div>

<!-- ================== GUR PROCESS ================== -->
<div class="section">
  <h2>The GUR process</h2>
  <div class="box split-3">
    <div>
      <h3>Step 1</h3>
      <p>We define research goals and identify target players.</p>
    </div>
    <div>
      <h3>Step 2</h3>
      <p>We conduct structured playtests and collect behavioral data.</p>
    </div>
    <div>
      <h3>Step 3</h3>
      <p>We analyze results and deliver clear, actionable insights.</p>
    </div>
  </div>
</div>

<!-- ================== PRICING ================== -->
<div class="section">
  <h2>Pricing</h2>
  <div class="box split-2">
    <div>
      <h3>Basic Package</h3>
      <p>Ideal for small teams looking for quick usability feedback.</p>
    </div>
    <div>
      <h3>Full Research Package</h3>
      <p>Comprehensive testing, reporting, and deep player insights.</p>
    </div>
  </div>
</div>

<!-- ================== CONTACT ================== -->
<div class="section contact">
  <h2>Contact</h2>
  <div class="box">
    <p>Email: your@email.com</p>
    <p>Discord: yourDiscord#0000</p>
  </div>
</div>
