<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Harvey Chiva | Father's Day Sci-Fi Portfolio</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Orbitron',sans-serif;
    background:#050816;
    color:#fff;
    overflow-x:hidden;
}

/* Animated background */
body::before{
    content:"";
    position:fixed;
    inset:0;
    background:
    radial-gradient(circle at 20% 20%, rgba(0,255,255,.15), transparent 30%),
    radial-gradient(circle at 80% 70%, rgba(255,0,255,.15), transparent 30%);
    animation: pulse 6s infinite alternate;
    z-index:-2;
}

@keyframes pulse{
    from{transform:scale(1);}
    to{transform:scale(1.2);}
}

.stars{
    position:fixed;
    inset:0;
    background-image:
    radial-gradient(white 1px, transparent 1px);
    background-size:50px 50px;
    opacity:.25;
    z-index:-1;
}

.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
}

.panel{
    border:2px solid cyan;
    padding:40px;
    border-radius:20px;
    background:rgba(0,0,0,.45);
    box-shadow:0 0 30px cyan;
    max-width:900px;
}

.hero h1{
    font-size:4rem;
    color:#00ffff;
    text-shadow:0 0 20px cyan;
}

.hero h2{
    margin-top:10px;
    color:#ffd700;
}

.hero p{
    margin-top:20px;
    line-height:1.8;
}

section{
    max-width:1000px;
    margin:auto;
    padding:80px 20px;
}

.card{
    background:rgba(255,255,255,.05);
    border:1px solid cyan;
    border-radius:15px;
    padding:25px;
    margin-bottom:25px;
    box-shadow:0 0 15px rgba(0,255,255,.3);
}

.card h3{
    color:#00ffff;
    margin-bottom:15px;
}

.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
}

.skill{
    padding:20px;
    text-align:center;
    border:1px solid cyan;
    border-radius:12px;
}

footer{
    text-align:center;
    padding:30px;
    border-top:1px solid cyan;
}

.glow{
    color:#ffd700;
    text-shadow:0 0 10px gold;
}
</style>
</head>
<body>

<div class="stars"></div>

<div class="hero">
    <div class="panel">
        <h1>HARVEY CHIVA</h1>
        <h2>FATHER'S DAY SCI-FI PORTFOLIO</h2>

        <p>
            <span class="glow">Mission Log:</span><br>
            Every hero has an origin. Mine begins with my father —
            my guide, my inspiration, and my strongest support system.
            This portfolio is dedicated to him.
        </p>
    </div>
</div>

<section>
    <div class="card">
        <h3>🚀 About Me</h3>
        <p>
            I'm Harvey Chiva, a student who enjoys technology,
            design, creativity, and futuristic concepts.
            I believe growth comes from discipline, curiosity,
            and the lessons passed down by family.
        </p>
    </div>

    <div class="card">
        <h3>💙 Father's Day Tribute</h3>
        <p>
            Thank you, Dad, for every sacrifice, lesson,
            and word of encouragement. Your guidance continues
            to help me navigate my journey toward the future.
        </p>
    </div>
</section>

<section>
    <h2 style="text-align:center;margin-bottom:30px;color:cyan;">
        Skills Database
    </h2>

    <div class="skills">
        <div class="skill">💻 Web Design</div>
        <div class="skill">🎨 Creative Design</div>
        <div class="skill">⚡ Technology</div>
        <div class="skill">🚴 Cycling</div>
    </div>
</section>

<section>
    <div class="card">
        <h3>🌌 Future Missions</h3>
        <p>
            • Build advanced web projects<br>
            • Learn more programming languages<br>
            • Create futuristic digital art<br>
            • Continue growing and making my family proud
        </p>
    </div>
</section>

<footer>
    <p>
        © 2026 Harvey Chiva • Dedicated to Dad • Happy Father's Day
    </p>
</footer>

</body>
</html>
