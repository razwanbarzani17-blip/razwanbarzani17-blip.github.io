<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Najwa ❤️ | 8-8</title>

    <!-- Instagram / WhatsApp link preview -->
    <meta property="og:title" content="Najwa ❤️">
    <meta property="og:description" content="A little piece of my heart, made just for you.">
    <meta property="og:type" content="website">

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            min-height: 100vh;
            overflow-x: hidden;
            font-family: Georgia, "Times New Roman", serif;
            color: white;
            background:
                radial-gradient(circle at 20% 20%, rgba(255, 105, 180, 0.25), transparent 30%),
                radial-gradient(circle at 80% 80%, rgba(150, 70, 255, 0.25), transparent 30%),
                linear-gradient(135deg, #12000d, #2b001c, #100014);
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 30px 15px;
            position: relative;
        }

        body::before {
            content: "";
            position: fixed;
            inset: 0;
            background-image:
                radial-gradient(white 1px, transparent 1px),
                radial-gradient(white 1px, transparent 1px);
            background-size: 70px 70px, 110px 110px;
            background-position: 0 0, 40px 50px;
            opacity: 0.15;
            pointer-events: none;
        }

        .card {
            width: 100%;
            max-width: 500px;
            padding: 45px 28px;
            text-align: center;
            border-radius: 30px;
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.18);
            backdrop-filter: blur(15px);
            box-shadow:
                0 25px 80px rgba(0, 0, 0, 0.5),
                0 0 60px rgba(255, 70, 150, 0.15);
            position: relative;
            z-index: 2;
        }

        .date {
            font-family: Arial, sans-serif;
            font-size: 13px;
            letter-spacing: 5px;
            text-transform: uppercase;
            opacity: 0.7;
            margin-bottom: 20px;
        }

        .heart {
            font-size: 65px;
            animation: heartbeat 1.5s infinite;
            filter: drop-shadow(0 0 20px rgba(255, 60, 130, 0.8));
        }

        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.15);
            }
        }

        h1 {
            font-size: clamp(45px, 13vw, 75px);
            margin: 10px 0;
            font-weight: normal;
            background: linear-gradient(90deg, #fff, #ffb6d9, #fff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 25px rgba(255, 150, 200, 0.3);
        }

        .subtitle {
            font-family: Arial, sans-serif;
            font-size: 16px;
            letter-spacing: 2px;
            opacity: 0.8;
            margin-bottom: 35px;
        }

        .message {
            font-size: 20px;
            line-height: 1.8;
            color: #ffe9f3;
            margin: 0 auto 25px;
        }

        .quote {
            font-style: italic;
            font-size: 17px;
            line-height: 1.7;
            color: #ffd0e4;
            margin: 25px 0;
        }

        .divider {
            width: 80px;
            height: 1px;
            background: rgba(255,255,255,0.5);
            margin: 30px auto;
        }

        .love-button {
            border: 1px solid rgba(255,255,255,0.25);
            background: rgba(255,255,255,0.1);
            color: white;
            padding: 14px 25px;
            border-radius: 50px;
            font-size: 15px;
            cursor: pointer;
            transition: 0.3s;
            margin-top: 10px;
        }

        .love-button:hover {
            background: rgba(255, 100, 170, 0.25);
            transform: scale(1.05);
        }

        #secret {
            display: none;
            margin-top: 25px;
            font-size: 18px;
            line-height: 1.7;
            color: #ffd9e8;
            animation: appear 1s ease;
        }

        @keyframes appear {
            from {
                opacity: 0;
                transform: translateY(10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .music {
            margin-top: 25px;
            font-family: Arial, sans-serif;
            font-size: 13px;
            opacity: 0.65;
        }

        .floating-heart {
            position: fixed;
            bottom: -30px;
            font-size: 20px;
            opacity: 0.6;
            animation: floatUp linear forwards;
            pointer-events: none;
            z-index: 1;
        }

        @keyframes floatUp {
            from {
                transform: translateY(0) rotate(0deg);
                opacity: 0;
            }
            15% {
                opacity: 0.7;
            }
            to {
                transform: translateY(-110vh) rotate(360deg);
                opacity: 0;
            }
        }

        .footer {
            margin-top: 30px;
            font-family: Arial, sans-serif;
            font-size: 12px;
            opacity: 0.45;
        }
    </style>
</head>

<body>

    <div class="card">

        <div class="date">8 • 8 • ❤️</div>

        <div class="heart">❤️</div>

        <h1>Najwa</h1>

        <div class="subtitle">I LOVE YOU</div>

        <div class="divider"></div>

        <p class="message">
            If I could give you one thing in life,
            I would give you the ability to see yourself
            through my eyes.
        </p>

        <p class="quote">
            "Because then you would finally understand
            how special you are to me."
        </p>

        <div class="divider"></div>

        <p class="message">
            I don't need a perfect story.
            I just want the little moments,
            the smiles, the memories,
            and a reason to keep choosing you.
        </p>

        <button class="love-button" onclick="showSecret()">
            Open my heart ❤️
        </button>

        <div id="secret">
            Najwa, wherever life takes us,
            a part of my heart will always remember
            this little date — <b>8-8</b>.
            <br><br>
            You are not just someone I love.
            You are someone I will always wish happiness for.
            ❤️
        </div>

        <div class="music">
            🎵 Tap the music button below when we add your song.
        </div>

        <audio id="song" controls style="width:100%; margin-top:15px;">
            <source src="music.mp3" type="audio/mpeg">
            Your browser does not support audio.
        </audio>

        <div class="footer">
            Made with ❤️ for Najwa
        </div>

    </div>

    <script>
        function showSecret() {
            document.getElementById("secret").style.display = "block";
        }

        function createHeart() {
            const heart = document.createElement("div");
            heart.className = "floating-heart";
            heart.innerHTML = Math.random() > 0.5 ? "❤️" : "♡";

            heart.style.left = Math.random() * 100 + "vw";
            heart.style.fontSize = (12 + Math.random() * 20) + "px";
            heart.style.animationDuration = (5 + Math.random() * 7) + "s";

            document.body.appendChild(heart);

            setTimeout(() => {
                heart.remove();
            }, 12000);
        }

        setInterval(createHeart, 900);
    </script>

</body>
</html>
