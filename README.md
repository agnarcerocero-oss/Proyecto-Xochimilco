<!DOCTYPE html>    

<html lang="es">    
<head>    
<meta charset="UTF-8">    
<title>Xochimilco</title>    

<style>    
body{font-family: Arial; margin: 0;background-color: #f4f4f4;}    

header{background-color: #2e8b57; color: white; padding: 15px;    
text-align: center;    
}    

nav ul{list-style: none; padding: 0px;}    

nav ul li{display: inline; margin: 10px;}    

nav a{ color: white; text-decoration: none; font-weight: bold;}    

section{ padding: 20px; margin: 10px; background: white; border-radius: 10px;}    

h2{ color: #2e8b57;}    

img{width: 200px; height: 200px; margin: 5px; border-radius: 10px;}    

button{background-color:crimson; color:white; padding:10px; border:none; border-radius: 8px; cursor: pointer;}    

button:hover{background-color: darkred;}    
</style>    
</head>    

<body>    

<header>    
<h1>
Xochimilco: 
<span style="color:darkgreen;">Gas</span><span style="color:withe">tro</span><span style="color:red;">nomía</span>, 
Historia y Tradición Viva
</h1>    
<nav>    
<ul>    
<li><a href="#gastronomia">Gastronomía</a></li>    
<li><a href="#historia">Historia</a></li>    
<li><a href="#tradiciones">Tradiciones</a></li>    
<li><a href="#canales">Canales</a></li>    
<li><a href="#galeria">Galería</a></li>    
<li><a href="#geografia">Geografía</a></li>    
</ul>    
</nav>    
</header>    

<section id="gastronomia">    
<h2>🍽️ Gastronomía en Xochimilco</h2>    

<p>Xochimilco no solo es famoso por sus canales, también por su gastronomía tradicional que forma parte de su identidad cultural.</p>    

<p>En los recorridos en trajinera es común encontrar alimentos típicos como quesadillas, elotes, esquites y tlacoyos, preparados de forma tradicional.</p>    

<p>Muchos de estos alimentos provienen de las chinampas, donde se cultivan productos como maíz, verduras y flores comestibles.</p>    

<button onclick="alert('La comida en Xochimilco proviene de tradiciones prehispánicas')">    
Importancia de la gastronomía    
</button>    

</section>    

<section>    
<p>Xochimilco es una de las zonas más representativas de la Ciudad de México por su riqueza histórica, cultural y natural.</p>    

<button onclick="alert('Xochimilco tiene más de 170 km de canales')">    
Dato curioso    
</button>    
</section>    

<section id="historia">    
<h2>📜 Historia</h2>    

<p><b>Origen prehispánico:</b> Fue fundado por pueblos indígenas que desarrollaron chinampas, donde también se cultivaban alimentos básicos.</p>    

<p><b>Época colonial:</b> Se mezclaron tradiciones indígenas y europeas, incluyendo la gastronomía.</p>    

<p><b>Actualidad:</b> Conserva su cultura, incluyendo su comida típica.</p>    
</section>    

<section id="tradiciones">    
<h2>🎭 Tradiciones</h2>    

<ul>    
<li>Día de la Candelaria</li>    
<li>Día de Muertos</li>    
<li>Fiestas patronales</li>    
</ul>    

<p>Las trajineras permiten disfrutar música, cultura y comida tradicional.</p>    
</section>    

<section id="canales">    
<h2>🌊 Canales y Chinampas</h2>    

<p>Los canales permitían transportar alimentos cultivados en chinampas.</p>    

<p>Las chinampas siguen siendo importantes para la producción de alimentos.</p>    

<button onclick="document.getElementById('info').innerHTML='El ajolote vive en estos canales y comparte ecosistema con zonas agrícolas.'">    
Ver dato ecológico    
</button>    

<p id="info"></p>    
</section>    

<section>    
<h2>⚽ Mundial 2026</h2>    

<p>Durante el Mundial, la gastronomía de Xochimilco puede atraer turistas internacionales.</p>    

<video width="300" height="200" controls>
<source src="video.mp4" type="video/mp4">
</video>

</section>    

<section id="galeria">    
<h2>📷 Galería</h2>    

<img src="trajineras.png">    
<img src="trajineras1.jpg">    
<img src="trajineras2.jpg">    
<img src="chinampas.webp">    
<img src="chinampas1.jpg">    
<img src="chinampas2.jpg">    
<img src="tradiciones.jpg">    
</section>    

<section id="geografia">    
<h2>🌎 Geografía y Clima</h2>    

<p>Xochimilco permite el cultivo de alimentos gracias a su clima y suelo fértil.</p>    

<ul>    
<li>Altitud: 2,240 msnm</li>    
<li>Clima templado</li>    
<li>Zona agrícola</li>    
</ul>    

<button onclick="document.getElementById('mapa').style.display='block'">    
Ver ubicación    
</button>    

<p id="mapa" style="display:none;">    
Ubicación: Sur de la CDMX    
</p>    
</section>    

<section>    
<h2>⚠️ Problemas actuales</h2>    

<ul>    
<li>Contaminación afecta la producción de alimentos</li>    
<li>Pérdida de chinampas</li>    
<li>Urbanización</li>    
</ul>    
</section>    

<section>    
<h2>💡 ¿Cómo ayudar?</h2>    

<ul>    
<li>Consumir productos locales</li>    
<li>Cuidar el ambiente</li>    
<li>Apoyar a productores</li>    
</ul>    

<button onclick="document.body.style.backgroundColor='lightgreen'">    
Modo ecológico 🌿    
</button>    
</section>    

<section>
<h2>🎮 Mini Quiz</h2>

<p>1. ¿Qué significa Xochimilco?</p>
<button onclick="alert('Correcto: Lugar de las flores 🌸')">Lugar de las flores</button>
<button onclick="alert('Incorrecto ❌')">Lugar del agua</button>

<p>2. ¿Qué sistema agrícola se usa en Xochimilco?</p>
<button onclick="alert('Correcto ✅')">Chinampas</button>
<button onclick="alert('Incorrecto ❌')">Invernaderos</button>

<p>3. ¿Qué alimento es típico en las trajineras?</p>
<button onclick="alert('Correcto ✅')">Quesadillas</button>
<button onclick="alert('Incorrecto ❌')">Pizza</button>

<p>4. ¿Qué animal vive en los canales?</p>
<button onclick="alert('Correcto ✅')">Ajolote</button>
<button onclick="alert('Incorrecto ❌')">Tigre</button>

<p>5. ¿Para qué servían los canales?</p>
<button onclick="alert('Correcto ✅')">Transporte de alimentos</button>
<button onclick="alert('Incorrecto ❌')">Solo turismo</button>

<p>6. ¿Qué se cultiva en chinampas?</p>
<button onclick="alert('Correcto ✅')">Maíz y verduras</button>
<button onclick="alert('Incorrecto ❌')">Plástico</button>

<p>7. ¿Qué bebida puedes encontrar en Xochimilco?</p>
<button onclick="alert('Correcto ✅')">Aguas frescas</button>
<button onclick="alert('Incorrecto ❌')">Refresco espacial</button>

<p>8. ¿Qué evento atraerá turistas a Xochimilco?</p>
<button onclick="alert('Correcto ✅')">Mundial 2026</button>
<button onclick="alert('Incorrecto ❌')">Olimpiadas 1800</button>

<p>9. ¿Qué problema afecta la gastronomía local?</p>
<button onclick="alert('Correcto ✅')">Contaminación</button>
<button onclick="alert('Incorrecto ❌')">Demasiada comida</button>

<p>10. ¿Cómo puedes ayudar a Xochimilco?</p>
<button onclick="alert('Correcto ✅')">Consumir productos locales</button>
<button onclick="alert('Incorrecto ❌')">Contaminar</button>

</section>

<section>
<h2>🍴 Platillos típicos</h2>
<p><b>Quesadillas:</b> Preparadas con maíz cultivado en chinampas.</p>
<p><b>Tlacoyos:</b> De origen prehispánico.</p>
<p><b>Elotes y esquites:</b> Vendidos en trajineras.</p>
</section>

<section>
<h2>🍽️ Gastronomía local vs turística</h2>
<p><b>Local:</b> Tradicional y de chinampas.</p>
<p><b>Turística:</b> Más comercial.</p>
</section>

<section>
<h2>📊 Datos curiosos</h2>
<ul>
<li>Más de 170 km de canales.</li>
<li>Chinampas únicas en el mundo.</li>
<li>Ingredientes cultivados localmente.</li>
<li>Hábitat del ajolote.</li>
</ul>
</section>

<section>
<h2>🏛️ Importancia de conservar la gastronomía</h2>
<p>La gastronomía conecta el pasado con el presente.</p>
<p>Conservarla protege la identidad cultural de México.</p>
</section>



<section>
<h2>📚 Bibliografía</h2>
<p>Gobierno de la Ciudad de México. (s.f.). Xochimilco. Recuperado de: 
<a href="https://www.cdmx.gob.mx</p">https://www.cdmx.gob.mx</a>

<p>UNESCO. (s.f.). Patrimonio Mundial: Xochimilco. Recuperado de: 
<a href="https://whc.unesco.org</p">https://whc.unesco.org</a>

<p>Secretaría de Turismo de México. (s.f.). Xochimilco y su gastronomía. Recuperado de: 
<a href="https://www.gob.mx/sectur</p">https://www.gob.mx/sectur</a>

<p>Instituto Nacional de Antropología e Historia (INAH). (s.f.). Historia de Xochimilco. Recuperado de: 
<a href="https://www.inah.gob.mx</p">https://www.inah.gob.mx</a>

<p>CONABIO. (s.f.). Ecosistemas y chinampas de Xochimilco. Recuperado de: 
<a href="https://www.biodiversidad.gob.mx">https://www.biodiversidad.gob.mx</a></p>

</section>

</head>
</html>



