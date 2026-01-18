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
  animation-name: skill-chaos;
  animation-duration: 6s;
  animation-iteration-count: infinite;
  animation-timing-function: ease-in-out;
  will-change: transform, opacity;
}

/* fake randomness */
.skills-container img:nth-child(odd) {
  animation-delay: 0.5s;
}

.skills-container img:nth-child(even) {
  animation-delay: 1s;
}

@keyframes skill-chaos {
  0% {
    transform: translate(0, 0) scale(1);
    opacity: 1;
  }

  25% {
    transform: translate(-15px, 20px) rotate(4deg) scale(1.1);
  }

  45% {
    transform: translate(20px, -15px) rotate(-4deg) scale(1.05);
  }

  65% {
    transform: translate(0, 0) scale(1);
    opacity: 1;
  }

  85% {
    transform: translate(150px, -150px) scale(0.6);
    opacity: 0;
  }

  100% {
    transform: translate(0, 0) scale(1);
    opacity: 1;
  }
}
</style>

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
