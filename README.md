<br>

<img align="left"
     src="https://user-images.githubusercontent.com/63050133/156777293-72a6e681-2582-4a9d-ad92-09d1181d47c7.gif"
     width="50px"
     height="50px">

<h2 align="left"><b>About me</b></h2>

<br><br>

./code_less/code-often

<br><br>

<h2><b>Skill Set</b></h2>

<!-- ================= SKILLS GRID ================= -->

<div class="skills-container">
  <img src="https://icon.icepanel.io/Technology/svg/React.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/Angular.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/Qwik.svg" />
  <img src="https://icon.icepanel.io/Technology/png-shadow-512/Next.js.png" />

  <img src="https://icon.icepanel.io/Technology/svg/Bun.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/Node.js.svg" />
  <img src="https://icon.icepanel.io/Technology/png-shadow-512/Flask.png" />
  <img src="https://icon.icepanel.io/Technology/png-shadow-512/Express.png" />
  <img src="https://elysiajs.com/assets/elysia.svg" />

  <img src="https://icon.icepanel.io/Technology/svg/MongoDB.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/MySQL.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/PostgresSQL.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/Firebase.svg" />
  <img src="https://icon.icepanel.io/Technology/png-shadow-512/Apache-Cassandra.png" />

  <img src="https://icon.icepanel.io/Technology/svg/Docker.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/Kubernetes.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/Digital-Ocean.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/Git.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/Heroku.svg" />

  <img src="https://icon.icepanel.io/Technology/svg/TypeScript.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/JavaScript.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/Python.svg" />
  <img src="https://icon.icepanel.io/Technology/svg/C.svg" />
  <img src="https://icon.icepanel.io/Technology/png-shadow-512/Bash.png" />
</div>

<!-- ================= CSS (README SAFE) ================= -->

<style>
.skills-container {
  display: grid;
  grid-template-columns: repeat(5, 80px);
  gap: 22px;
  justify-content: center;
  margin-top: 20px;
}

.skills-container img {
  width: 75px;
  animation: skill-chaos 8s infinite ease-in-out;
  will-change: transform, opacity;
}

/* staggered delays to simulate randomness */
.skills-container img:nth-child(3n) {
  animation-delay: 0.6s;
}
.skills-container img:nth-child(4n) {
  animation-delay: 1.2s;
}
.skills-container img:nth-child(5n) {
  animation-delay: 1.8s;
}

/* alternate motion direction */
.skills-container img:nth-child(even) {
  animation-direction: alternate-reverse;
}

@keyframes skill-chaos {
  /* organized grid */
  0% {
    transform: translate(0, 0) scale(1);
    opacity: 1;
  }

  /* floating chaos */
  20% {
    transform: translate(-18px, 14px) rotate(4deg) scale(1.08);
  }

  35% {
    transform: translate(16px, -12px) rotate(-4deg) scale(1.05);
  }

  /* re-organize */
  55% {
    transform: translate(0, 0) scale(1);
    opacity: 1;
  }

  /* blast off */
  80% {
    transform: translate(220px, -220px) scale(0.6);
    opacity: 0;
  }

  /* reset */
  100% {
    transform: translate(0, 0) scale(1);
    opacity: 1;
  }
}
</style>
