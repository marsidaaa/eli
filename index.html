<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Love Letter</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    * { box-sizing: border-box; margin:0; padding:0; }
    body {
      font-family: 'Poppins', cursive;
      background: #ffeaf1;
      overflow-x: hidden;
      position: relative;
      height: 100vh;
    }
    .container {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align: center;
      position: relative;
      z-index: 10;
    }

    .title-text {
      font-size: 2.5rem;
      color: #e91e63;
      font-weight: bold;
      margin-bottom: 20px;
      user-select: none;
    }

    .envelope-wrapper {
      width: 350px;
      height: 210px;
      perspective: 1200px;
      position: relative;
      cursor: pointer;
      z-index: 10;
    }
    .envelope {
      width: 100%;
      height: 100%;
      position: absolute;
      top: 0; left: 0;
      transform-style: preserve-3d;
      transition: transform 1s ease-in-out;
    }
    .envelope-body {
      width: 100%;
      height: 100%;
      background: #ffe4ec;
      border: 2px solid #e91e63;
      border-radius: 4px;
      position: absolute;
      box-shadow: inset 0 0 8px rgba(0, 0, 0, 0.1), 0 5px 15px rgba(233, 30, 99, 0.2);
      transform: translateZ(-1px);
    }
    .envelope-flap {
      width: 100%;
      height: 50%;
      background: linear-gradient(to bottom, #ffccd9, #ffb6c1);
      clip-path: polygon(0 0, 100% 0, 50% 100%);
      position: absolute;
      top: 0; left: 0;
      transform-origin: top center;
      box-shadow: 0 4px 5px rgba(233, 30, 99, 0.3);
      transition: transform 0.1s ease-in-out;
    }
    .envelope.opened .envelope-flap {
      transform: rotateX(-180deg);
    }
    .envelope.opened {
      transform: translateY(-30px);
    }

    .card-container {
      display: none;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      gap: 20px;
      width: 350px;
      max-width: 90vw;
      z-index: 10;
      padding: 0;
      text-align: center;
    }

    .card, .card.image-card {
      background: #fff;
      border-radius: 16px;
      width: 350px;
      max-width: 90vw;
      padding: 20px;
      position: relative;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1), 0 0 0 1px #e4d0d0;
      background-image: radial-gradient(#fff 40%, #f9f0f2 100%);
      background-blend-mode: overlay;
      transition: transform 0.6s ease, opacity 0.6s ease;
      transform-style: preserve-3d;
      text-align: center;
    }

    .card.anim-exit {
      transform: translateX(-100%) rotateY(-90deg);
      opacity: 0;
    }
    .card.anim-enter {
      transform: translateX(100%) rotateY(90deg);
      opacity: 0;
    }
    .card.visible {
      transform: translateX(0) rotateY(0deg);
      opacity: 1;
    }

    .card p {
      color: #555;
      font-size: 1.2rem;
      line-height: 1.4;
    }

    .card.image-card img {
      width: 250px;
      max-width: 90vw;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      display: block;
      margin: 0 auto;
    }

    .heart-decor {
      position: absolute;
      top: 12px; right: 12px;
      width: 17px; height: 17px;
      background: linear-gradient(135deg, #ff4f8b, #e91e63);
      transform: rotate(45deg);
      box-shadow: 0 1px 4px rgba(0,0,0,0.2);
    }
    .heart-decor::before, .heart-decor::after {
      content: '';
      width: 17px; height: 17px;
      background: linear-gradient(135deg, #ff4f8b, #e91e63);
      position: absolute;
      border-radius: 50%;
    }
    .heart-decor::before { top: -8.5px; left: 0; }
    .heart-decor::after { top: 0; left: -8.5px; }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 20px;
      width: 100%;
      max-width: 350px;
    }
    .next-button, .back-button {
      background: #e91e63;
      color: white;
      padding: 12px 0;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      font-size: 1.2em;
      width: 50%;
      font-weight: bold;
      box-shadow: 0 4px 10px rgba(233, 30, 99, 0.6);
      transition: background 0.3s;
      user-select: none;
    }
    .next-button:hover, .back-button:hover {
      background: #c2185b;
    }
    .back-button {
      display: none;
    }

    .floating-hearts {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      pointer-events: none;
      z-index: -1;
    }
    .heart {
      position: absolute;
      width: 20px; height: 20px;
      background: red;
      transform: rotate(45deg);
      animation: float 6s linear infinite;
      opacity: 0.6;
    }
    .heart::before, .heart::after {
      content: '';
      position: absolute;
      width: 20px; height: 20px;
      background: red;
      border-radius: 50%;
    }
    .heart::before { top: -10px; left: 0; }
    .heart::after { top: 0; left: -10px; }

    @keyframes float {
      0% { transform: translateY(0) rotate(45deg); opacity: 1; }
      100% { transform: translateY(-100vh) rotate(45deg); opacity: 0; }
    }
  </style>
</head>
<body>

<div class="floating-hearts" id="floatingHearts"></div>

<div class="container" id="envelopeSection">
  <div class="title-text">Happy Anniversary!!!</div>
  <div class="envelope-wrapper" id="envelopeWrapper" aria-label="Click to open the envelope">
    <div class="envelope" id="envelope">
      <div class="envelope-body"></div>
      <div class="envelope-flap"></div>
    </div>
  </div>
  <p style="margin-top: 20px; color: #e91e63; font-weight: bold;">Kindly click the envelope po, I love youu!</p>
</div>

<div class="card-container" id="cardContainer">
  <div class="card" id="card">
    <div class="heart-decor"></div>
    <p id="cardMessage">Message will appear here.</p>
  </div>

  <div class="card image-card" id="imageCard" style="display: block;">
    <img src="ilovee.jpg" alt="Romantic image" />
  </div>

  <div class="buttons">
    <button class="back-button" id="backButton">Back</button>
    <button class="next-button" id="nextButton">Next</button>
  </div>
</div>

<script>
  const messages = [
     "hi babeee, finally our anniversaryyy, but first I want to say sorry if ito lang kinaya ko huhu, yk I'm broke,and as much as i badly want to shower you with gift, im just so broken right now, huhuness wrong timing to. so i though maybe i can just pour my heart out here and tried to code this website to send you love letter na lang (i hope this work). wala na nga ako maibigay sayo kada monthsary natin tapos pati ba naman anniversary? It may not be much pero sana maramdaman mo kung gaano kita kamahal through every word i write. excuse my grahams na lang babe ah, trigger warning⚠️ to bekus my english is not beri beri good and broken like meh hehe.",
    "it's been a months babe, a months of loving each other haha parang nung nakaraan lang magka away pa tayo eh jusme. yk what sobrang mahal na mahal kita di ko lang talaga kayang iexpress sayo kase it's so madami (ung pagmamahal ko ah). it's overflowing, lahat ng moments wit you kahit gaano ka simple ay sobrang precious sakin kase wtf, even if we're already together na I'm still crushing on you like HAHAHAHAHAHA may mga time na madalas pa rin akong kiligin sayo magkasama man tayo o hindi wala talaga pinipili, pinipigilan ko na lang kase inaasar mo ko eh mwehehehehe (wag kase hiya ako ehh). You're beautiful and when you smile, it's the prettiest thing I've ever seen, kaya wag mong sabihin na nag sisisi ako sayo porke naaabutan mokong naka titig sayo, I just can't stop it yk, masyadong akong inlove sayo hehe.",
    "I love you so much, I love everything about you and I think you're perfect. Every time we talk or call i get so excited  and burst out with joy na akala mo batang binilhan ng laruan HAHAHAHA. I genuinely hope na sana makasal tayo someday kase i cant see my future without you, you're literally my everything. I want to grow with you, I want to kiss you more and cuddle you huhu, I miss you so muchhhhh!! I want you to tanan me na so i can have unlimited love, kisses, hugs, cuddles from you.🥹",
    "and yk what ikaw lang taong gusto kong ulit ulitin ung moments with you. ung tipong kahit pare parehas lang ginagawa natin, hinding hindi talaga ako magsasawa kase i love you so much, you make everything feel new and special js by being there. honestly, sa lahat ng naging relationship ko, sayo ko lang naranasan ung ganito sa totoo lang. I feel like it's my first time to be loved like this, ang sarap nya sa feeling and gusto ko maramdaman to araw araw, gusto ko ng laging ganito, mamahalin moko at mamahalin kita nang sobra sobra. i literally love you so much even this paragraphs is not enough to explain it, baka tamarin kapa bigla while reading it. I love you now and i always will. wag mo isipin na iiwan kita ha, I'm not going anywhere, Im not leaving you po okay? I want to stay here with you (gusto mo pumulupot pa ako sayo e 😏).",
    "let's continue growing together, I can't promise na magiging perfect girlfriend ako for you kase alam ko sa sarili ko na puno rin ako redflags hehe. pero i can promise you na i will never stop loving you kahit may problema pa yan o away we'll fix it together okay? I love you so much babe, whether in good or in bad condition, I'll be with you for the rest of my life",
    "I don't have gifts now babe, it's just me and i, writing this paragraphs with this munting website of mine and this is also my first time doin' this, so, hope you like it🥹. I love you so muchhh, and happy anniversary!!! 1 year down and a lifetime to go (⁠≧⁠▽⁠≦⁠)"
      ];

  let currentIndex = 0;

  const envelope = document.getElementById('envelope');
  const envelopeSection = document.getElementById('envelopeSection');
  const cardContainer = document.getElementById('cardContainer');
  const card = document.getElementById('card');
  const cardMessage = document.getElementById('cardMessage');
  const nextButton = document.getElementById('nextButton');
  const backButton = document.getElementById('backButton');
  const imageCard = document.getElementById('imageCard');

  document.getElementById('envelopeWrapper').onclick = () => {
    envelope.classList.add('opened');
    setTimeout(() => {
      envelopeSection.style.display = 'none';
      cardContainer.style.display = 'flex';
      showMessage(currentIndex, true);
      updateButtons();
    }, 1000);
  };

  nextButton.onclick = () => {
    if (currentIndex < messages.length) {
      showMessage(currentIndex + 1, false);
      currentIndex++;
      updateButtons();
    }
  };

  backButton.onclick = () => {
    if (currentIndex > 0) {
      showMessage(currentIndex - 1, false);
      currentIndex--;
      updateButtons();
    }
  };

  function showMessage(index, instant = false) {
    if (index === messages.length) {
      card.style.display = 'none';
      imageCard.style.display = 'block';
    } else {
      imageCard.style.display = 'none';
      card.style.display = 'block';
      if (!instant) {
        card.classList.remove('visible');
        card.classList.add('anim-exit');
        setTimeout(() => {
          updateCard(index);
          card.classList.remove('anim-exit');
          card.classList.add('anim-enter');
          setTimeout(() => {
            card.classList.remove('anim-enter');
            card.classList.add('visible');
          }, 20);
        }, 400);
      } else {
        updateCard(index);
        card.classList.add('visible');
      }
    }
  }

  function updateCard(idx) {
    cardMessage.textContent = messages[idx];
  }

  function updateButtons() {
    backButton.style.display = currentIndex === 0 ? 'none' : 'inline-block';
    nextButton.style.display = currentIndex === messages.length ? 'none' : 'inline-block';
  }

  // Floating hearts
  const floatingHearts = document.getElementById('floatingHearts');
  function createHeart() {
    const h = document.createElement('div');
    h.classList.add('heart');
    h.style.left = Math.random() * 100 + 'vw';
    h.style.animationDuration = 3 + Math.random() * 3 + 's';
    h.style.opacity = Math.random().toFixed(2);
    h.style.transform = `scale(${(Math.random() + 0.5).toFixed(2)}) rotate(45deg)`;
    floatingHearts.appendChild(h);
    setTimeout(() => h.remove(), 6000);
  }
  setInterval(createHeart, 300);
</script>

</body>
</html>
