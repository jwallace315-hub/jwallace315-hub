<link href="https://fonts.googleapis.com/css2?family=Jost:wght@300;400;600&display=swap" rel="stylesheet">

<!-- ================== STYLES ================== -->
<style>
/* Remove repo name */
header, .markdown-body > h1:first-child {
  display: none;
}
  
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

  width: 100vw;
  margin-left: calc(-50vw + 50%);
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
  background-color: #e9e9e6;
  border: 1px solid #d6d6d2;
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

/* Removes anchor links */
.anchorjs-link,
.octicon-link,
a.anchor {
  display: none !important;
}
.markdown-body h1 a,
.markdown-body h2 a,
.markdown-body h3 a {
  display: none !important;
}
  
/* Add smooth scrolling */
html {
  scroll-behavior: smooth;
}
</style>

<!-- ================== NAVBAR ================== -->
<div class="navbar">
  GurNFriends
  <span style="float:right; font-weight:400;">
    <a href="#what-we-do" style="color:white; margin:0 10px; text-decoration:none;">What We Do</a>
    <a href="#process" style="color:white; margin:0 10px; text-decoration:none;">Process</a>
    <a href="#pricing" style="color:white; margin:0 10px; text-decoration:none;">Pricing</a>
    <a href="#contact" style="color:white; margin:0 10px; text-decoration:none;">Contact</a>
  </span>
</div>

<!-- ================== WHAT WE DO ================== -->
<div class="section" id="what-we-do">
  <h2>What it is we do</h2>
  <div class="box">
    <p>
      We run playtests with participants in your target audience to help you make your intended experience. 
      Instead of having to make adjustments to your design and codebase later down the line, costing you your time and money, 
      we can highlight those issues before it requires much earlier before it requires significant changes. 
      <hr>
      Depending on your needs we can address anything from basic usability fixes to granular user experience tweaks to specific mechanics.
    </p>
  </div>
</div>

<!-- ================== GUR PROCESS ================== -->
<div class="section" id="process">
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
<div class="section" id="pricing">
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
<div class="section" id="contact">
  <h2>Contact</h2>
  <div class="box">
    <p>Email: your@email.com</p>
    <p>Discord: yourDiscord#0000</p>
  </div>
</div>
