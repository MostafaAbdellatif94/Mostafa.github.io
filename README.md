<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mostafa | Software Developer</title>

<style>

/* ===== GENERAL ===== */
body{
    margin:0;
    font-family: Arial, sans-serif;
    background:#0b1220;
    color:white;
    line-height:1.6;
}

a{color:white;text-decoration:none;}

.container{
    width:90%;
    max-width:1100px;
    margin:auto;
}

/* ===== NAVBAR ===== */
nav{
    background:#111a30;
    padding:15px;
    position:sticky;
    top:0;
    text-align:center;
}

nav a{
    margin:0 15px;
    font-weight:bold;
}

nav a:hover{
    color:#00d4ff;
}

/* ===== HERO ===== */
.hero{
    padding:60px 20px;
    text-align:center;
    background:linear-gradient(135deg,#7c5cff,#00d4ff);
}

.hero h1{
    margin:10px 0;
    font-size:40px;
}

/* ===== INITIAL ICON ===== */
.initial{
    width:120px;
    height:120px;
    border-radius:50%;
    margin:auto;
    background:white;
    color:#0b1220;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:40px;
    font-weight:bold;
    margin-bottom:15px;
}

/* ===== SECTIONS ===== */
section{
    padding:50px 20px;
}

.section-title{
    text-align:center;
    margin-bottom:30px;
}

/* ===== CARDS ===== */
.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:#111a30;
    padding:20px;
    border-radius:12px;
}

/* ===== SKILLS ===== */
.skills span{
    display:inline-block;
    background:#00d4ff;
    color:#000;
    padding:6px 12px;
    margin:5px;
    border-radius:20px;
    font-weight:bold;
}

/* ===== CONTACT FORM ===== */
form input, form textarea{
    width:100%;
    padding:10px;
    margin:10px 0;
    border:none;
    border-radius:6px;
}

button{
    background:#00d4ff;
    border:none;
    padding:12px;
    width:100%;
    font-weight:bold;
    border-radius:6px;
    cursor:pointer;
}

button:hover{
    background:#7c5cff;
    color:white;
}

/* ===== FOOTER ===== */
footer{
    background:#111a30;
    text-align:center;
    padding:15px;
}

</style>
</head>

<body>

<!-- NAVIGATION -->
<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<!-- HERO -->
<section id="home" class="hero">
    <div class="container">

        <!-- INITIAL ICON -->
        <div class="initial">M</div>

        <h1>Hi, I'm Mostafa</h1>
        <p>
            Software Developer and father of a daughter.
            I am currently studying Software and Web Development at The Tech Academy.
            I have loved creating games and applications since I was young.
        </p>

    </div>
</section>

<!-- ABOUT -->
<section id="about">
    <div class="container">
        <h2 class="section-title">About Me</h2>

        <div class="grid">
            <div class="card">
                <h3>Who I Am</h3>
                <p>I am a passionate software developer who loves building applications and games.</p>
            </div>

            <div class="card">
                <h3>My Goal</h3>
                <p>To become a professional developer and create powerful applications and websites.</p>
            </div>

            <div class="card">
                <h3>Education</h3>
                <p>Currently studying Software & Web Development at The Tech Academy.</p>
            </div>
        </div>
    </div>
</section>

<!-- SKILLS -->
<section id="skills" style="background:#0f1a30;">
    <div class="container">
        <h2 class="section-title">Skills</h2>

        <div class="skills" style="text-align:center;">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
            <span>Problem Solving</span>
            <span>Web Development</span>
        </div>
    </div>
</section>

<!-- PROJECTS -->
<section id="projects">
    <div class="container">
        <h2 class="section-title">Projects</h2>

        <div class="grid">
            <div class="card">
                <h3>Game Project</h3>
                <p>A simple game I created while learning programming basics.</p>
            </div>

            <div class="card">
                <h3>One page Website</h3>
                <p>This website built using HTML & CSS.</p>
            </div>

            <div class="card">
                <h3>Web App</h3>
                <p> A bootstrap4_project.</p>
            </div>
        </div>
    </div>
</section>

<!-- CONTACT -->
<section id="contact" style="background:#0f1a30;">
    <div class="container">
        <h2 class="section-title">Contact Me</h2>

        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message"></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Mostafa | Software Developer Portfolio</p>
</footer>

</body>
</html>
