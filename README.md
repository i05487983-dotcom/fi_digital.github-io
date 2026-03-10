<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>FI Digital — Digital Marketing Agency</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;700;800&display=swap" rel="stylesheet">

<style>

:root{
--bg:#EAF5F1;
--accent:#2F7F6D;
--dark:#0F3F35;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Inter,sans-serif;
scroll-behavior:smooth;
}

body{
background:var(--bg);
color:var(--dark);
}

section{
padding:100px 10%;
}

h1{
font-size:64px;
font-weight:800;
line-height:1.1;
}

h2{
font-size:40px;
margin-bottom:40px;
}

p{
font-size:18px;
opacity:.8;
}

.grid{
display:grid;
gap:30px;
}

.btn{
display:inline-block;
padding:14px 26px;
background:var(--accent);
color:white;
border-radius:30px;
text-decoration:none;
font-weight:600;
transition:.3s;
box-shadow:0 0 20px rgba(47,127,109,.3);
}

.btn:hover{
transform:translateY(-3px);
box-shadow:0 0 30px rgba(47,127,109,.6);
}

.card{
background:rgba(255,255,255,.4);
backdrop-filter:blur(12px);
padding:30px;
border-radius:16px;
border:1px solid rgba(255,255,255,.3);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
box-shadow:0 20px 40px rgba(0,0,0,.08);
}

.hero{
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
background:
radial-gradient(circle at top,rgba(47,127,109,.2),transparent 60%);
}

.hero p{
margin:20px 0 30px;
font-size:20px;
}

.services-grid{
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
}

.results-grid{
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
}

.process-grid{
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
}

.dark{
background:var(--dark);
color:white;
}

.dark p{
opacity:.9;
}

.contact-form{
display:flex;
flex-direction:column;
gap:15px;
max-width:500px;
}

input,textarea{
padding:14px;
border-radius:10px;
border:none;
outline:none;
font-size:16px;
}

textarea{
height:120px;
}

footer{
text-align:center;
padding:40px;
font-size:14px;
opacity:.6;
}

.glow{
position:absolute;
width:500px;
height:500px;
background:radial-gradient(circle,var(--accent),transparent 70%);
filter:blur(120px);
opacity:.2;
z-index:-1;
animation:float 6s infinite alternate;
}

@keyframes float{
from{transform:translateY(-40px)}
to{transform:translateY(40px)}
}

</style>
</head>

<body>

<div class="glow"></div>

<section class="hero">

<div>

<h1>FI Digital</h1>

<p>Elite digital marketing agency helping brands scale with strategy, creativity and automation.</p>

<a href="#contact" class="btn">Contact Us</a>

</div>

</section>


<section>

<h2>Services</h2>

<div class="grid services-grid">

<div class="card">
<h3>SMM</h3>
<p>Strategic social media growth on TikTok, Instagram and modern platforms.</p>
</div>

<div class="card">
<h3>Paid Ads</h3>
<p>Performance-driven advertising campaigns that generate real ROI.</p>
</div>

<div class="card">
<h3>Branding</h3>
<p>Premium brand identity and positioning for modern digital companies.</p>
</div>

<div class="card">
<h3>Content Strategy</h3>
<p>Content systems designed to attract traffic and convert audiences.</p>
</div>

<div class="card">
<h3>AI Automation (soon)</h3>
<p>Advanced AI workflows to scale marketing and customer acquisition.</p>
</div>

</div>

</section>


<section class="dark">

<h2>Results</h2>

<div class="grid results-grid">

<div class="card">
<h3>+240%</h3>
<p>Average social media growth for our clients.</p>
</div>

<div class="card">
<h3>3M+</h3>
<p>Views generated through content strategy.</p>
</div>

<div class="card">
<h3>$120K+</h3>
<p>Revenue generated from paid advertising campaigns.</p>
</div>

</div>

</section>


<section>

<h2>Our Process</h2>

<div class="grid process-grid">

<div class="card">
<h3>1. Discovery</h3>
<p>We analyze your brand, market and audience.</p>
</div>

<div class="card">
<h3>2. Strategy</h3>
<p>We design a clear growth system for your brand.</p>
</div>

<div class="card">
<h3>3. Execution</h3>
<p>Content, ads and growth campaigns launched.</p>
</div>

<div class="card">
<h3>4. Scaling</h3>
<p>We optimize and scale profitable strategies.</p>
</div>

</div>

</section>


<section class="dark">

<h2>About FI Digital</h2>

<p style="max-width:700px">
FI Digital is a modern digital marketing agency focused on helping brands grow through high performance content, paid advertising and strategic brand positioning.  
Our mission is to build elite digital presence for ambitious companies.
</p>

</section>


<section>

<h2>Client Reviews</h2>

<div class="grid results-grid">

<div class="card">
<p>"Amazing work. Our Instagram grew 5x in 2 months."</p>
<strong>— Alex, Clothing Brand</strong>
</div>

<div class="card">
<p>"FI Digital helped us launch ads that brought our first 20k revenue."</p>
<strong>— Daniel, E-commerce</strong>
</div>

<div class="card">
<p>"Professional strategy and very strong content ideas."</p>
<strong>— Mark, Startup Founder</strong>
</div>

</div>

</section>


<section id="contact" class="dark">

<h2>Contact Us</h2>

<div style="display:flex;gap:60px;flex-wrap:wrap">

<form class="contact-form">

<input placeholder="Your Name">

<input placeholder="Email">

<textarea placeholder="Tell us about your project"></textarea>

<button class="btn">Send Message</button>

</form>


<div>

<p><strong>Email</strong></p>
<p>illiahigh7@gmail.com</p>

<br>

<p><strong>Phone</strong></p>
<p>+38 068 540 3251</p>

<br>

<a class="btn" href="mailto:illiahigh7@gmail.com">Email Us</a>

<br><br>

<a class="btn" href="tel:+380685403251">Call Us</a>

</div>

</div>

</section>


<footer>

© 2026 FI Digital — Digital Marketing Agency

</footer>


<script>

const cards=document.querySelectorAll(".card");

cards.forEach(card=>{
card.addEventListener("mousemove",e=>{
const rect=card.getBoundingClientRect();
const x=e.clientX-rect.left;
const y=e.clientY-rect.top;
card.style.transform=`rotateX(${-(y-rect.height/2)/20}deg) rotateY(${(x-rect.width/2)/20}deg)`;
});
card.addEventListener("mouseleave",()=>{
card.style.transform="rotateX(0) rotateY(0)";
});
});

</script>

</body>
</html>
