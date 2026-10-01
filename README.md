<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>A Letter For You 💗</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=Quicksand:wght@400;500;600;700&display=swap');

*{box-sizing:border-box}
html,body{
  width:100%;height:100%;margin:0;
}
body{
  overflow:hidden;
  font-family:Quicksand,sans-serif;
  color:#694d56;
  background:#fff7fa;
}
body:before{
  content:"";position:fixed;inset:0;pointer-events:none;opacity:.22;
  background-image:radial-gradient(#eea8bd .7px,transparent .7px);
  background-size:8px 8px;
}
.screen{
  width:100vw;height:100dvh;
  display:flex;align-items:center;justify-content:center;
  position:relative;padding:22px;
}
.petal{
  position:fixed;z-index:0;font-size:18px;opacity:.38;
  animation:float 7s linear infinite;pointer-events:none;
}
.p1{left:8%;top:82%}.p2{left:88%;top:70%;animation-delay:2s}
.p3{left:17%;top:25%;animation-delay:4s}.p4{left:78%;top:17%;animation-delay:5s}
@keyframes float{
  0%{transform:translateY(0) rotate(0)}100%{transform:translateY(-90vh) rotate(180deg)}
}

/* INTRO */
.intro{
  width:100%;max-width:430px;text-align:center;z-index:5;
  transition:.8s ease;
}
.intro.hide{opacity:0;transform:scale(.92);pointer-events:none}
.small{
  color:#d9859f;font-size:11px;letter-spacing:4px;
  text-transform:uppercase;font-weight:700;
}
.intro h1{
  font-family:"DM Serif Display",serif;font-weight:400;
  color:#bd6682;font-size:45px;line-height:1.08;
  margin:12px 0 10px;
}
.intro p{font-size:14px;color:#a17b87;margin:0 0 28px}
.open{
  border:0;border-radius:30px;background:#e995ae;color:white;
  padding:14px 27px;font:700 13px Quicksand;
  letter-spacing:1px;box-shadow:0 9px 22px #d8799635;
  cursor:pointer;
}

/* ENVELOPE */
.envelope{
  position:absolute;width:min(84vw,360px);height:235px;
  transition:1s ease;z-index:3;cursor:pointer;
}
.envelope.opened{opacity:0;transform:scale(.75) translateY(70px);pointer-events:none}
.env{
  position:absolute;inset:0;border-radius:10px;
  background:#f4c5d3;box-shadow:0 20px 40px #b75d7930;
}
.front{
  position:absolute;inset:0;z-index:3;border-radius:10px;
  clip-path:polygon(0 0,50% 54%,100% 0,100% 100%,0 100%);
  background:#edb1c3;
}
.flap{
  position:absolute;left:0;top:0;width:100%;height:62%;z-index:4;
  background:#f8d6df;clip-path:polygon(0 0,100% 0,50% 100%);
  transform-origin:top;transition:1s ease;
}
.envelope.opened .flap{transform:rotateX(180deg)}
.seal{
  position:absolute;z-index:6;left:50%;top:51%;
  transform:translate(-50%,-50%);
  width:57px;height:57px;border-radius:50%;
  display:grid;place-items:center;background:#d97996;color:white;
  font-size:25px;box-shadow:0 6px 13px #9d506a30;
  transition:.5s;
}
.envelope.opened .seal{opacity:0;transform:translate(-50%,-50%) scale(.3)}

/* PAPER */
.paper{
  position:absolute;z-index:8;
  width:calc(100vw - 28px);max-width:430px;
  height:calc(100dvh - 28px);
  background:#fff;
  border:1px solid #f7dce4;
  border-radius:22px;
  box-shadow:0 15px 50px #b75d7925;
  padding:40px 27px 30px;
  overflow-y:auto;
  opacity:0;transform:translateY(40px) scale(.96);
  pointer-events:none;transition:.8s ease;
}
.paper.show{opacity:1;transform:translateY(0) scale(1);pointer-events:auto}
.paper:before{
  content:"";position:absolute;inset:13px;border:1px solid #f7e2e8;
  border-radius:16px;pointer-events:none;
}
.paper>*{position:relative;z-index:2}
.close{
  position:absolute;right:23px;top:19px;z-index:5;
  border:0;background:#fff0f4;color:#cf7892;
  width:31px;height:31px;border-radius:50%;font-size:19px;cursor:pointer;
}
.top-heart{text-align:center;font-size:25px;color:#df8da5}
.date{
  text-align:center;color:#d88aa0;font-size:10px;
  letter-spacing:3px;text-transform:uppercase;margin-top:10px;
}
.paper h2{
  font-family:"DM Serif Display",serif;font-weight:400;
  color:#bd6682;text-align:center;
  font-size:38px;line-height:1.05;margin:17px 0 25px;
}
.message{
  font-size:14.5px;line-height:1.85;color:#765b64;
}
.message p{margin:0 0 17px}
.signature{
  font-family:"DM Serif Display",serif;
  text-align:center;color:#c87891;font-size:25px;margin-top:24px;
}
.bottom{text-align:center;color:#e095ab;font-size:18px;margin-top:15px}
.note{text-align:center;font-size:10px;color:#b99aa4;margin-top:12px}

.music{
  position:fixed;right:17px;top:17px;z-index:20;
  width:42px;height:42px;border:1px solid #f0c9d5;
  border-radius:50%;background:#fff;color:#cf7892;
  font-size:17px;cursor:pointer;box-shadow:0 5px 18px #b75d7918;
}
@media(max-height:650px){
  .paper{padding-top:32px}.paper h2{font-size:32px;margin:12px 0 18px}
  .message{font-size:13.5px}.message p{margin-bottom:12px}
}
</style>
</head>
<body>

<div class="petal p1">♡</div>
<div class="petal p2">♡</div>
<div class="petal p3">✿</div>
<div class="petal p4">♡</div>

<button class="music" id="musicBtn" onclick="toggleMusic()">♫</button>

<main class="screen">

  <section class="intro" id="intro">
    <div class="small">a little something for you</div>
    <h1>I wrote you<br>a letter. ♡</h1>
    <p>Take a moment, open it slowly.</p>
    <button class="open" onclick="openLetter()">OPEN MY LETTER</button>
  </section>

  <div class="envelope" id="envelope" onclick="openLetter()">
    <div class="env"></div>
    <div class="flap"></div>
    <div class="front"></div>
    <div class="seal">♡</div>
  </div>

  <article class="paper" id="paper">
    <button class="close" onclick="closeLetter()">×</button>

    <div class="top-heart">♡</div>
    <div class="date">from my heart to yours</div>

    <h2> I love you, Kozume.</h2>

    <div class="message">
      <p>
        I don't know if words will ever be enough to explain how much
        you mean to me, but I still want to try.
      </p>

      <p>
        Somewhere along the way, you became my favorite person.
        You became the person I look for in a crowd, the name that
        makes me smile when it appears on my screen, and the thought
        that somehow makes an ordinary day feel special.
      </p>

      <p>
        I love all the little things about you. Your smile, your
        silly side, the way you talk, and even the tiny things you
        probably don't realize I notice.
      </p>

      <p>
        Thank you for being here. Thank you for making me happy in
        ways you may never know. If I had to choose again, in another
        life and another story, I think I would still find my way to you.
      </p>

      <p>
        So whenever you miss me, come back to this little letter.
        Let it remind you that somewhere, someone is always rooting
        for you, caring about you, and loving you a little more every day.
      </p>
    </div>

    <div class="signature">Always yours ♡</div>
    <div class="bottom">♡ &nbsp; ♡ &nbsp; ♡</div>
    <div class="note">keep this letter close to your heart</div>
  </article>
</main>

<audio id="song" loop>
  <source src="https://cdn.pixabay.com/audio/2022/10/30/audio_9463b7f3c6.mp3" type="audio/mpeg">
</audio>
<script>
const intro=document.getElementById("intro");
const envelope=document.getElementById("envelope");
const paper=document.getElementById("paper");
const song=document.getElementById("song");
const musicBtn=document.getElementById("musicBtn");

function openLetter(){
  intro.classList.add("hide");
  envelope.classList.add("opened");
  setTimeout(()=>paper.classList.add("show"),650);

<script>
const song = document.getElementById("song");
const musicBtn = document.getElementById("musicBtn");

song.volume = 0.70;

function startMusic() {
  song.play()
    .then(() => {
      musicBtn.textContent = "♫";
    })
    .catch(() => {
      musicBtn.textContent = "🔇";
    });
}

function openLetter() {
  document.getElementById("intro").classList.add("hide");
  document.getElementById("envelope").classList.add("opened");

  startMusic();

  setTimeout(() => {
    document.getElementById("paper").classList.add("show");
  }, 650);
}

function closeLetter() {
  document.getElementById("paper").classList.remove("show");

  setTimeout(() => {
    document.getElementById("envelope").classList.remove("opened");
    document.getElementById("intro").classList.remove("hide");
  }, 500);
}
 <audio id="song" src="./you.mp3" loop preload="auto"></audio>
</script>
</body>
</html>
