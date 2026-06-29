<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ajit Mahto | Portfolio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:#0f172a;
color:white;
}

header{
padding:80px 20px;
text-align:center;
background:linear-gradient(135deg,#0f172a,#1e3a8a);
}

header h1{
font-size:55px;
margin-bottom:10px;
}

header h3{
color:#38bdf8;
margin-bottom:20px;
}

.btn{
display:inline-block;
padding:12px 25px;
background:#38bdf8;
color:white;
text-decoration:none;
border-radius:30px;
margin:10px;
transition:.3s;
}

.btn:hover{
background:#0ea5e9;
transform:scale(1.05);
}

section{
max-width:1100px;
margin:auto;
padding:60px 20px;
}

h2{
text-align:center;
margin-bottom:30px;
color:#38bdf8;
font-size:35px;
}

.about{
text-align:center;
font-size:18px;
line-height:1.8;
}

.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
gap:20px;
}

.skill{
background:#1e293b;
padding:20px;
text-align:center;
border-radius:10px;
transition:.3s;
}

.skill:hover{
transform:translateY(-8px);
background:#2563eb;
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:#1e293b;
padding:25px;
border-radius:10px;
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.contact{
text-align:center;
font-size:18px;
}

.contact a{
color:#38bdf8;
text-decoration:none;
}

footer{
background:#1e293b;
text-align:center;
padding:25px;
margin-top:50px;
}

</style>

</head>

<body>

<header>

<h1>Ajit Mahto</h1>

<h3>Java Full Stack Developer</h3>

<p>Spring Boot | React | Java | MySQL | HTML | CSS | JavaScript</p>

<br>

<a class="btn" href="https://github.com/Ajit3693" target="_blank">GitHub</a>

<a class="btn" href="#">Download Resume</a>

</header>

<section>

<h2>About Me</h2>

<p class="about">

I am a passionate Java Full Stack Developer with experience in Java, Spring Boot,
React, MySQL, HTML, CSS and JavaScript. I enjoy building responsive,
user-friendly and scalable web applications.

</p>

</section>

<section>

<h2>Skills</h2>

<div class="skills">

<div class="skill">Java</div>

<div class="skill">Spring Boot</div>

<div class="skill">React</div>

<div class="skill">MySQL</div>

<div class="skill">HTML5</div>

<div class="skill">CSS3</div>

<div class="skill">JavaScript</div>

<div class="skill">Bootstrap</div>

<div class="skill">Git</div>

<div class="skill">GitHub</div>

</div>

</section>

<section>

<h2>Projects</h2>

<div class="projects">

<div class="card">

<h3>Employee Management System</h3>

<p>
CRUD application using Java Spring Boot and MySQL.
</p>

</div>

<div class="card">

<h3>Student Management System</h3>

<p>
Full Stack project developed using Spring Boot and React.
</p>

</div>

<div class="card">

<h3>Portfolio Website</h3>

<p>
Responsive Portfolio Website using HTML, CSS and JavaScript.
</p>

</div>

</div>

</section>

<section>

<h2>Contact</h2>

<div class="contact">

<p><b>Name:</b> Ajit Mahto</p>

<p><b>GitHub:</b><br>

<a href="https://github.com/Ajit3693" target="_blank">
https://github.com/Ajit3693
</a>

</p>

<p><b>Email:</b> your-email@example.com</p>

<p><b>Location:</b> Bengaluru, India</p>

</div>

</section>

<footer>

<h3>© 2026 Ajit Mahto</h3>

<p>Designed with ❤️ by Ajit Mahto</p>

</footer>

<script>

const cards=document.querySelectorAll(".card,.skill");

window.addEventListener("scroll",()=>{

cards.forEach(card=>{

card.style.opacity="1";

});

});

console.log("Portfolio Loaded Successfully");

</script>

</body>
</html>
