<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Najwa ❤️ | 8•8</title>

<meta property="og:title" content="Najwa ❤️">
<meta property="og:description" content="Some feelings deserve their own little universe.">
<meta property="og:type" content="website">

<style>

*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Georgia,"Times New Roman",serif;
    background:#05000a;
    color:white;
    overflow-x:hidden;
}

/* NIGHT SKY */

.sky{
    position:fixed;
    inset:0;
    z-index:-5;
    background:
    radial-gradient(circle at 20% 20%,#4b123e 0%,transparent 30%),
    radial-gradient(circle at 80% 70%,#24105c 0%,transparent 35%),
    linear-gradient(180deg,#030006,#12000f,#050008);
}

/* STARS */

.stars{
    position:fixed;
    inset:0;
    z-index:-4;
    background-image:
    radial-gradient(white 1px,transparent 1px),
    radial-gradient(white 1px,transparent 1px),
    radial-gradient(#ffb6d9 1px,transparent 1px);
    background-size:90px 90px,130px 130px,180px 180px;
    background-position:10px 20px,50px 70px,30px 100px;
    opacity:.45;
    animation:starsMove 30s linear infinite;
}

@keyframes starsMove{
    from{transform:translateY(0);}
    to{transform:translateY(-100px);}
}

/* SECTIONS */

section{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:60px 20px;
    position:relative;
}

.container{
    width:100%;
    max-width:520px;
    text-align:center;
}

/* HERO */

.hero{
    min-height:100vh;
}

.small-date{
    font-family:Arial,sans-serif;
    font-size:12px;
    letter-spacing:6px;
    opacity:.65;
    margin-bottom:30px;
}

.big-heart{
    font-size:80px;
    animation:heartbeat 1.5s infinite;
    filter:drop-shadow(0 0 30px #ff3b8d);
}

@keyframes heartbeat{
    0%,100%{transform:scale(1);}
    50%{transform:scale(1.18);}
}

h1{
    font-size:clamp(55px,15vw,90px);
    font-weight:normal;
    margin:15px 0;
    background:linear-gradient(90deg,#fff,#ff9acb,#fff);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

.hero-sub{
    font-family:Arial,sans-serif;
    letter-spacing:4px;
    font-size:14px;
    opacity:.7;
}

.scroll{
    position:absolute;
    bottom:30px;
    font-family:Arial,sans-serif;
    font-size:11px;
    letter-spacing:3px;
    opacity:.5;
}

/* GLASS CARD */

.card{
    background:rgba(255,255,255,.07);
    border:1px solid rgba(255,255,255,.15);
    border-radius:30px;
    padding:38px 28px;
    backdrop-filter:blur(15px);
    box-shadow:
    0 30px 80px rgba(0,0,0,.5),
    0 0 50px rgba(255,60,150,.08);
}

/* LETTER */

.envelope{
    font-size:55px;
    margin-bottom:15px;
}

h2{
    font-size:36px;
    font-weight:normal;
    margin-bottom:25px;
}

.text{
    font-size:18px;
    line-height:1.9;
    color:#ffe6f1;
}

.signature{
    margin-top:30px;
    font-size:20px;
    font-style:italic;
    color:#ffb8d6;
}

/* BUTTON */

button{
    border:1px solid rgba(255,255,255,.25);
    background:rgba(255,255,255,.08);
    color:white;
    padding:14px 24px;
    border-radius:50px;
    font-size:14px;
    cursor:pointer;
    transition:.3s;
    margin-top:25px;
}

button:hover{
    transform:scale(1.05);
    background:rgba(255,70,150,.2);
}

/* SECRET */

.secret{
    display:none;
    margin-top:25px;
    animation:fade .8s ease;
}

@keyframes fade{
    from{opacity:0;transform:translateY(15px);}
    to{opacity:1;transform:translateY(0);}
}

/* PHOTO SECTION */

.photos{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:12px;
    margin-top:25px;
}

.photo{
    height:180px;
    border-radius:20px;
    background:
    linear-gradient(135deg,rgba(255,90,160,.2),rgba(80,40,150,.3));
    border:1px solid rgba(255,255,255,.12);
    display:flex;
    justify-content:center;
    align-items:center;
    font-family:Arial,sans-serif;
    font-size:12px;
    opacity:.7;
    overflow:hidden;
}

.photo img{
    width:100%;
    height:100%;
    object-fit:cover;
}

/* REASONS */

.reason{
    padding:18px 0;
    border-bottom:1px solid rgba(255,255,255,.1);
    font-size:18px;
}

.reason:last-child{
    border:none;
}

/* MUSIC */

.music-box{
    margin-top:25px;
}

audio{
    width:100%;
    margin-top:15px;
}

/* FINAL */

.final{
    text-align:center;
}

.final-heart{
    font-size:65px;
    margin-bottom:25px;
}

.final h2{
    font-size:40px;
}

.final p{
    font-size:18px;
    line-height:1.8;
    color:#ffd9e8;
}

.date-big{
    margin-top:35px;
    font-size:30px;
    color:#ff9dca;
    letter-spacing:5px;
}

/* FLOATING HEARTS */

.floating{
    position:fixed;
    bottom:-40px;
    pointer-events:none;
    z-index:10;
    animation:floatUp linear forwards;
}

@keyframes floatUp{
    from{
        transform:translateY(0) rotate(0);
        opacity:0;
    }
    15%{opacity:.8;}
    to{
        transform:translateY(-110vh) rotate(360deg);
        opacity:0;
    }
}

/* SHOOTING STAR */

.shooting{
    position:fixed;
    width:100px;
    height:2px;
    background:linear-gradient(90deg,transparent,#fff);
    transform:rotate(-35deg);
    animation:shoot 5s linear infinite;
    opacity:0;
}

@keyframes shoot{
    0%{
        left:100%;
        top:10%;
        opacity:0;
    }
    5%{opacity:1;}
    15%{
        left:70%;
        top:30%;
        opacity:0;
    }
    100%{opacity:0;}
}

/* FOOTER */

footer{
    text-align:center;
    padding:40px 20px;
    font-family:Arial,sans-serif;
    font-size:11px;
    opacity:.4;
}

</style>
</head>

<body>

<div class="sky"></div>
<div class="stars"></div>
<div class="shooting"></div>

<!-- HERO -->

<section class="hero">

<div class="container">

<div class="small-date">
8 • 8 • 2026
</div>

<div class="big-heart">
❤️
</div>

<h1>Najwa</h1>

<div class="hero-sub">
I LOVE YOU
</div>

</div>

<div class="scroll">
↓ SCROLL SLOWLY ↓
</div>

</section>


<!-- LETTER -->

<section>

<div class="container">

<div class="card">

<div class="envelope">
💌
</div>

<h2>A little letter for you</h2>

<p class="text">

Najwa,

sometimes words are not enough to explain
what someone means to you.

So I made this little place in the world
just for you.

Not because I know how to write
the perfect love story...

but because you are someone
worth writing one for.

</p>

<div class="signature">
— From my heart ❤️
</div>

</div>

</div>

</section>


<!-- SECRET MESSAGE -->

<section>

<div class="container">

<div class="card">

<h2>There is something hidden...</h2>

<p class="text">
Maybe you should press the button.
</p>

<button onclick="openSecret()">
Open my heart ❤️
</button>

<div class="secret" id="secret">

<p class="text">

If I could give you one thing,
I would give you the ability
to see yourself through my eyes.

Then you would understand
why you are so special to me.

And if I could choose one memory
to keep forever...

I would choose the moments
where you smiled.

❤️

</p>

</div>

</div>

</div>

</section>


<!-- PHOTOS -->

<section>

<div class="container">

<div class="card">

<h2>Our little memories 📸</h2>

<p class="text">
Some moments deserve to stay forever.
</p>

<div class="photos">

<div class="photo">
YOUR PHOTO ❤️
</div>

<div class="photo">
YOUR PHOTO ❤️
</div>

<div class="photo">
YOUR PHOTO ❤️
</div>

<div class="photo">
YOUR PHOTO ❤️
</div>

</div>

<p style="margin-top:20px;opacity:.5;font-family:Arial;font-size:12px;">
We'll replace these with your real photos.
</p>

</div>

</div>

</section>


<!-- REASONS -->

<section>

<div class="container">

<div class="card">

<h2>Why you are special ❤️</h2>

<div class="reason">
Because your smile can change a whole day.
</div>

<div class="reason">
Because some people simply feel different.
</div>

<div class="reason">
Because memories with you stay longer.
</div>

<div class="reason">
Because you became a beautiful part of my thoughts.
</div>

<div class="reason">
And simply... because you are you.
</div>

</div>

</div>

</section>


<!-- MUSIC -->

<section>

<div class="container">

<div class="card">

<h2>Our song 🎵</h2>

<p class="text">
Every love story needs a song.
</p>

<div class="music-box">

<audio controls>
<source src="music.mp3" type="audio/mpeg">
Your browser does not support audio.
</audio>

<p style="margin-top:15px;opacity:.5;font-family:Arial;font-size:12px;">
Tap ▶️ and listen.
</p>

</div>

</div>

</div>

</section>


<!-- FINAL -->

<section>

<div class="container final">

<div class="final-heart">
❤️
</div>

<h2>For Najwa</h2>

<p>

I don't know what tomorrow will bring.

But I know that today,
I wanted you to know
that you are loved.

Take care of yourself.

Keep smiling.

And whenever you see this date...

remember that somewhere,
someone was thinking about you.

</p>

<div class="date-big">
8 • 8
</div>

</div>

</section>


<footer>
Made with ❤️
</footer>


<script>

/* SECRET */

function openSecret(){

    const secret=document.getElementById("secret");

    secret.style.display="block";

}


/* FLOATING HEARTS */

function createHeart(){

    const heart=document.createElement("div");

    heart.className="floating";

    const hearts=["❤️","💗","💖","💕","♡"];

    heart.innerHTML=hearts[
        Math.floor(Math.random()*hearts.length)
    ];

    heart.style.left=Math.random()*100+"vw";

    heart.style.fontSize=
        (12+Math.random()*22)+"px";

    heart.style.animationDuration=
        (6+Math.random()*8)+"s";

    document.body.appendChild(heart);

    setTimeout(()=>{
        heart.remove();
    },15000);

}

setInterval(createHeart,900);

</script>

</body>
</html>
