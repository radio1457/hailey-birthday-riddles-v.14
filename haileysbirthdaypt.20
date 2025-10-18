<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Sweet Birthday Girl &lt;3</title>
<style>
body {
  margin: 0;
  padding: 0;
  background-color: #ffd6ec;
  background-image: repeating-linear-gradient(
      45deg,
      rgba(255, 255, 255, 0.3) 0 20px,
      rgba(255, 182, 193, 0.3) 20px 40px
    ),
    url("data:image/svg+xml;utf8,\
<svg xmlns='http://www.w3.org/2000/svg' width='120' height='120'>\
<text x='5' y='25' font-size='22'>😺</text>\
<text x='50' y='60' font-size='22'>🐾</text>\
<text x='80' y='40' font-size='20'>^_^</text>\
<text x='30' y='90' font-size='22'>💕</text>\
</svg>");
  background-size: 120px 120px;
  font-family: "Comic Sans MS", cursive, sans-serif;
  overflow: hidden;
}

.page {
  display: none;
  text-align: center;
  padding: 20px;
}
.page.active {
  display: block;
}
h1 {
  font-size: 2.2em;
  color: #ff69b4;
  margin-top: 100px;
}
p {
  font-size: 1.2em;
}
.button {
  background-color: #ffb6c1;
  border: none;
  padding: 10px 25px;
  margin-top: 20px;
  border-radius: 20px;
  font-size: 1.1em;
  cursor: pointer;
}
.button:hover {
  background-color: #ffa6c9;
}
.floating {
  position: absolute;
  animation: float 3s ease-in-out infinite alternate;
  font-size: 1.5em;
}
@keyframes float {
  0% { transform: translateY(0); }
  100% { transform: translateY(-10px); }
}

/* Letters at the bottom (slightly raised) */
#letterContainer {
  position: fixed;
  bottom: 60px;
  left: 50%;
  transform: translateX(-50%);
  font-size: 2em;
  display: flex;
  gap: 10px;
  z-index: 20;
}

/* Gift code non-cursive */
.gift-code {
  font-family: monospace;
  background: white;
  padding: 5px 10px;
  border-radius: 8px;
  font-size: 1.2em;
}

/* Confetti */
.confetti {
  position: fixed;
  width: 10px;
  height: 10px;
  background-color: pink;
  animation: fall 4s linear infinite;
  z-index: 5;
}
@keyframes fall {
  0% { transform: translateY(-10px) rotate(0deg); }
  100% { transform: translateY(100vh) rotate(720deg); }
}

/* Glowing title & fade-in text */
.glow-title {
  text-shadow: 0 0 8px #fff, 0 0 16px #ff69b4, 0 0 24px #ffc0cb;
  animation: glowPulse 2s ease-in-out infinite alternate;
}
@keyframes glowPulse {
  from { text-shadow: 0 0 8px #fff, 0 0 16px #ff69b4; }
  to { text-shadow: 0 0 20px #fff, 0 0 30px #ff1493; }
}
.fade-in {
  opacity: 0;
  animation: fadeInText 2s ease-in forwards;
}
.fade-in.delay1 { animation-delay: 1s; }
.fade-in.delay2 { animation-delay: 2s; }
@keyframes fadeInText {
  from { opacity: 0; transform: translateY(10px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>
</head>
<body>

<div id="page1" class="page active">
  <h1>🎉 Happy Birthday Sweet Birthday Girl &lt;3 🎉</h1>
  <button class="button" id="startBtn">Start 🎂</button>
  <span class="floating" style="top:40%;left:20%;">😺</span>
  <span class="floating" style="top:50%;left:60%;">🐱</span>
  <span class="floating" style="top:70%;left:30%;">😸</span>
</div>

<div id="letterContainer"></div>

<!-- Riddle pages -->
<div id="riddle1" class="page">
  <h1>💖 Riddle 1 🐾</h1>
  <p>It beats with love inside your chest,<br>It’s full of feelings and never rests 💗</p>
  <input type="text" id="ans1" placeholder="Your answer..."><br>
  <button class="button" id="submit1">Submit 💕</button>
  <p id="msg1"></p>
</div>

<div id="riddle2" class="page">
  <h1>🍎 Riddle 2 🐾</h1>
  <p>I’m red or green and grow on trees,<br>Crunchy and juicy, I’m quite the tease 🍏</p>
  <input type="text" id="ans2" placeholder="Your answer..."><br>
  <button class="button" id="submit2">Submit 💕</button>
  <p id="msg2"></p>
</div>

<div id="riddle3" class="page">
  <h1>❄️ Riddle 3 🐾</h1>
  <p>I’m cold, I melt, I make drinks nice,<br>I’m tiny, clear, and made of ice 🧊</p>
  <input type="text" id="ans3" placeholder="Your answer..."><br>
  <button class="button" id="submit3">Submit 💕</button>
  <p id="msg3"></p>
</div>

<div id="riddle4" class="page">
  <h1>💡 Riddle 4 🐾</h1>
  <p>I shine when it’s dark and help you see,<br>I live in lamps and glow for thee ✨</p>
  <input type="text" id="ans4" placeholder="Your answer..."><br>
  <button class="button" id="submit4">Submit 💕</button>
  <p id="msg4"></p>
</div>

<div id="riddle5" class="page">
  <h1>🌸 Riddle 5 🐾</h1>
  <p>I’m the fifth letter, easy to see,<br>I’m right in your name and start “energy” 🌼</p>
  <input type="text" id="ans5" placeholder="Your answer..."><br>
  <button class="button" id="submit5">Submit 💕</button>
  <p id="msg5"></p>
</div>

<div id="riddle6" class="page">
  <h1>⭐ Riddle 6 🐾</h1>
  <p>I’m the last letter, I end your name,<br>Guess me right to win the game 😸</p>
  <input type="text" id="ans6" placeholder="Your answer..."><br>
  <button class="button" id="submit6">Submit 💕</button>
  <p id="msg6"></p>
</div>

<div id="page7" class="page">
  <h1>🎁 You spelled me out! 🎁</h1>
  <p>What’s your name? :D</p>
  <input type="text" id="nameInput" placeholder="Type your name..."><br>
  <button class="button" id="submitName">Submit 💖</button>
  <p id="message"></p>
</div>

<!-- Final Page -->
<div id="page8" class="page">
  <h1 class="glow-title">🎉 Happy Birthday Little One! 🎉 😸</h1>
  <p class="final-text fade-in">
    ¡Te deseo un gran día, ey también que te quiero mucho, y espero más para ti chiquita :D! 💕🐾
  </p>
  <p class="fade-in delay1">
    Here’s a Starbucks gift card since I know you like your coffee 😚 
    <span class="gift-code">GEJAKKAJF</span>
  </p>
  <p class="fade-in delay2">
    There’s one more surprise but you’ll find that part out soon enough little one 😊<br>
    I hope you enjoyed this along with everything else you’ve received for your birthday 🎉🎂!!!
  </p>
  <span class="floating" style="top:10%; left:20%;">😺</span>
  <span class="floating" style="top:50%; left:50%;">🐱</span>
  <span class="floating" style="top:80%; left:70%;">😸</span>
</div>

<script>
document.addEventListener('DOMContentLoaded',function(){
  const letters=['H','A','I','L','E','Y'];
  const answers=['heart','apple','ice','lamp','e','y'];

  function nextPage(id){
    document.querySelector('.page.active').classList.remove('active');
    document.getElementById(id).classList.add('active');
  }

  document.getElementById('startBtn').addEventListener('click',()=>{ nextPage('riddle1'); });

  for(let i=1;i<=6;i++){
    document.getElementById(`submit${i}`).addEventListener('click',()=>{
      let ans=document.getElementById(`ans${i}`).value.trim().toLowerCase();
      if(ans===answers[i-1]){
        document.getElementById('letterContainer').innerHTML+=letters[i-1];
        if(i<6) nextPage(`riddle${i+1}`); else nextPage('page7');
      } else { document.getElementById(`msg${i}`).textContent='Try again! 😺'; }
    });
  }

  document.getElementById('submitName').addEventListener('click',()=>{
    if(document.getElementById('nameInput').value.trim().toLowerCase()==='hailey'){
      nextPage('page8');
    } else { document.getElementById('message').textContent='Hmm… that doesn’t match! :3'; }
  });

  // Confetti background
  for(let i=0;i<80;i++){
    const c=document.createElement('div');
    c.classList.add('confetti');
    c.style.left=Math.random()*100+'vw';
    c.style.backgroundColor=['#ffb6c1','#ff69b4','#ffc0cb','#ffe4e1'][Math.floor(Math.random()*4)];
    c.style.animationDuration=3+Math.random()*3+'s';
    document.body.appendChild(c);
  }

  // Extra confetti burst for the final page 🎊
  const observer = new MutationObserver(() => {
    const lastPage = document.getElementById('page8');
    if (lastPage.classList.contains('active')) {
      for (let i = 0; i < 100; i++) {
        const c = document.createElement('div');
        c.classList.add('confetti');
        c.style.left = Math.random() * 100 + 'vw';
        c.style.backgroundColor = ['#ffb6c1', '#ff69b4', '#ffc0cb', '#ffe4e1', '#fff0f5'][Math.floor(Math.random() * 5)];
        c.style.animationDuration = 2 + Math.random() * 2 + 's';
        c.style.width = 8 + Math.random() * 8 + 'px';
        c.style.height = 8 + Math.random() * 8 + 'px';
        c.style.opacity = 0.9;
        document.body.appendChild(c);
        setTimeout(() => c.remove(), 4000);
      }
    }
  });

  observer.observe(document.body, { attributes: true, subtree: true, attributeFilter: ['class'] });
});
</script>
</body>
</html>
