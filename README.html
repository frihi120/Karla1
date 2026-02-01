<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>Happy Birthday Karla ✨</title>

<style>
  body {
    margin: 0;
    font-family: "Segoe UI", Arial, sans-serif;
    background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);
    height: 100vh;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
  }

  .card {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    padding: 40px;
    border-radius: 25px;
    text-align: center;
    max-width: 420px;
    box-shadow: 0 0 40px rgba(255, 150, 200, 0.5);
    animation: fadeIn 2s ease;
    z-index: 2;
  }

  h1 {
    color: #ffb6d5;
    margin-bottom: 10px;
    font-size: 32px;
  }

  p {
    font-size: 18px;
    line-height: 1.5;
    color: #f1f1f1;
  }

  button {
    margin-top: 20px;
    padding: 12px 28px;
    border: none;
    border-radius: 30px;
    background: #ff5e9c;
    color: white;
    font-size: 16px;
    cursor: pointer;
    transition: 0.3s;
  }

  button:hover {
    background: #ff2f7d;
    transform: scale(1.1);
  }

  .hidden {
    display: none;
  }

  canvas {
    position: absolute;
    top: 0;
    left: 0;
    z-index: 1;
  }

  .flower {
    position: absolute;
    font-size: 24px;
    animation: floatFlower 6s linear infinite;
    pointer-events: none;
  }

  @keyframes floatFlower {
    from {
      transform: translateY(100vh) rotate(0deg);
      opacity: 1;
    }
    to {
      transform: translateY(-10vh) rotate(360deg);
      opacity: 0;
    }
  }

  @keyframes fadeIn {
    from {
      opacity: 0;
      transform: scale(0.8);
    }
    to {
      opacity: 1;
      transform: scale(1);
    }
  }
</style>
</head>
<body>

<canvas id="fireworks"></canvas>

<audio id="music" loop>
  <source src="https://cdn.pixabay.com/audio/2023/03/27/audio_94b4c9fdd2.mp3" type="audio/mpeg">
</audio>

<div class="card">
  <h1>🎉 Happy Birthday Karla 🎉</h1>

  <p id="mainText">
    Today is special, not just because it’s your birthday — but because the world got someone like you.
  </p>

  <button onclick="startMagic()">Click for your surprise ✨</button>

  <p id="surpriseText" class="hidden">
    I’m really grateful I get to talk to you and share moments like this.  
    I hope this year brings you smiles, calm days, and everything beautiful you deserve 💫
  </p>
</div>

<script>
  // FIREWORKS
  const canvas = document.getElementById("fireworks");
  const ctx = canvas.getContext("2d");

  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;

  window.addEventListener("resize", () => {
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
  });

  let particles = [];

  function random(min, max) {
    return Math.random() * (max - min) + min;
  }

  function createFirework(x, y) {
    const count = 60;
    for (let i = 0; i < count; i++) {
      particles.push({
        x: x,
        y: y,
        angle: Math.random() * Math.PI * 2,
        speed: random(2, 6),
        radius: 2,
        alpha: 1,
        decay: random(0.01, 0.02),
        color: `hsl(${Math.random() * 360}, 100%, 70%)`
      });
    }
  }

  function updateFireworks() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);

    particles.forEach((p, index) => {
      p.x += Math.cos(p.angle) * p.speed;
      p.y += Math.sin(p.angle) * p.speed;
      p.alpha -= p.decay;

      if (p.alpha <= 0) {
        particles.splice(index, 1);
      } else {
        ctx.beginPath();
        ctx.globalAlpha = p.alpha;
        ctx.fillStyle = p.color;
        ctx.arc(p.x, p.y, p.radius, 0, Math.PI * 2);
        ctx.fill();
      }
    });

    ctx.globalAlpha = 1;
    requestAnimationFrame(updateFireworks);
  }

  // FLOWERS
  function createFlower() {
    const flower = document.createElement("div");
    flower.className = "flower";
    flower.innerHTML = ["🌸", "🌷", "🌹", "💐"][Math.floor(Math.random() * 4)];
    flower.style.left = Math.random() * 100 + "vw";
    flower.style.fontSize = Math.random() * 20 + 16 + "px";
    flower.style.animationDuration = random(4, 7) + "s";

    document.body.appendChild(flower);

    setTimeout(() => {
      flower.remove();
    }, 7000);
  }

  function startMagic() {
    document.getElementById("surpriseText").classList.remove("hidden");

    const music = document.getElementById("music");
    music.volume = 0.4;
    music.play();

    setInterval(() => {
      const x = random(100, canvas.width - 100);
      const y = random(100, canvas.height / 2);
      createFirework(x, y);
    }, 600);

    setInterval(() => {
      createFlower();
    }, 500);
  }

  updateFireworks();
</script>

</body>
</html>
