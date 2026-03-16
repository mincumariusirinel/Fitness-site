# Da  
  
<!DOCTYPE html>  
<html lang="ro">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1">  
  
<title>Elite Fitness Coaching</title>  
  
<style>  
  
body{  
margin:0;  
font-family:Arial;  
background:#0f0f0f;  
color:white;  
}  
  
header{  
text-align:center;  
padding:60px;  
background:url("https://images.unsplash.com/photo-1550345332-09e3ac987658");  
background-size:cover;  
}  
  
header h1{  
font-size:50px;  
}  
  
nav{  
background:black;  
padding:15px;  
text-align:center;  
}  
  
nav a{  
color:white;  
margin:15px;  
text-decoration:none;  
font-weight:bold;  
}  
  
section{  
padding:60px;  
max-width:1100px;  
margin:auto;  
}  
  
.card{  
background:#1c1c1c;  
padding:30px;  
margin:20px;  
border-radius:10px;  
}  
  
button{  
background:#ff2e2e;  
color:white;  
padding:12px 25px;  
border:none;  
cursor:pointer;  
}  
  
input{  
padding:10px;  
margin:5px;  
}  
  
.grid{  
display:grid;  
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));  
gap:20px;  
}  
  
footer{  
text-align:center;  
padding:30px;  
background:black;  
}  
  
</style>  
</head>  
  
<body>  
  
<header>  
<h1>Elite Fitness Coaching</h1>  
<p>Transformă-ți corpul. Transformă-ți viața.</p>  
<button>Începe acum</button>  
</header>  
  
<nav>  
<a href="#servicii">Servicii</a>  
<a href="#antrenamente">Antrenamente</a>  
<a href="#diete">Diete</a>  
<a href="#calculator">Calculator</a>  
<a href="#contact">Contact</a>  
</nav>  
  
<section id="servicii">  
<h2>Servicii</h2>  
  
<div class="grid">  
  
<div class="card">  
<h3>Plan antrenament</h3>  
<p>Program personalizat pentru obiectivul tău.</p>  
</div>  
  
<div class="card">  
<h3>Plan alimentar</h3>  
<p>Diete adaptate pentru slăbit sau masă.</p>  
</div>  
  
<div class="card">  
<h3>Coaching online</h3>  
<p>Monitorizare și suport permanent.</p>  
</div>  
  
</div>  
</section>  
  
<section id="antrenamente">  
<h2>Antrenamente</h2>  
  
<div class="card">  
<h3>Antrenament piept</h3>  
<ul>  
<li>Împins la bancă 4x10</li>  
<li>Fluturări gantere 3x12</li>  
<li>Dips 3x10</li>  
</ul>  
</div>  
  
</section>  
  
<section id="diete">  
<h2>Diete</h2>  
  
<div class="card">  
<h3>Dietă pentru masă musculară</h3>  
<ul>  
<li>Mic dejun: ovăz + ouă</li>  
<li>Prânz: orez + pui</li>  
<li>Cină: somon + legume</li>  
</ul>  
</div>  
  
</section>  
  
<section id="calculator">  
  
<h2>Calculator calorii</h2>  
  
<input type="number" id="kg" placeholder="Greutate kg">  
<input type="number" id="cm" placeholder="Înălțime cm">  
<input type="number" id="age" placeholder="Vârstă">  
  
<br><br>  
  
<button onclick="calc()">Calculează</button>  
  
<p id="result"></p>  
  
</section>  
  
<section id="contact">  
  
<h2>Contact</h2>  
  
<p>Email: contact@elitefitness.ro</p>  
<p>Instagram: @elitefitness</p>  
  
</section>  
  
<footer>  
<p>© 2026 Elite Fitness Coaching</p>  
</footer>  
  
<script>  
  
function calc(){  
  
let kg=document.getElementById("kg").value  
let cm=document.getElementById("cm").value  
let age=document.getElementById("age").value  
  
let calories=10*kg+6.25*cm-5*age+5  
  
document.getElementById("result").innerHTML=  
"Necesar caloric: "+calories+" kcal"  
  
}  
  
</script>  
  
</body>  
</html>  
