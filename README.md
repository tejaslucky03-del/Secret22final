
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>For Arjoo 💖</title>
<style>
*{box-sizing:border-box}
:root{--pink:#ff4f9a;--purple:#9b5cff;--ink:#71305f}
body{
 margin:0;min-height:100vh;font-family:Georgia,serif;
 color:var(--ink);text-align:center;overflow-x:hidden;
 background:linear-gradient(135deg,#ffe0f0,#e6d9ff,#c9f5ff,#fff0c9);
 background-size:300% 300%;animation:bg 12s ease infinite
}
@keyframes bg{0%,100%{background-position:0% 50%}50%{background-position:100% 50%}}
*{scroll-behavior:smooth}
.screen{
 min-height:100vh;padding:35px 16px;display:flex;flex-direction:column;
 align-items:center;justify-content:center;position:relative;z-index:1
}
.hidden{display:none!important}
h1{font-size:clamp(30px,8vw,45px);color:#ef3f91;text-shadow:0 3px 12px #ff8ec355}
h2{color:#a44cda}
p{font-size:17px;line-height:1.8}
.small{font-size:13px}
button{
 font-size:16px;font-weight:bold;color:white;
 border:0;border-radius:30px;padding:14px 22px;margin:10px 5px;
 background:linear-gradient(110deg,#ff4f9a,#a855f7);
 box-shadow:0 7px 20px #b34b9c44;cursor:pointer;
 transition:transform .25s,filter .25s
}
button:active{transform:scale(.94)}
button:hover{filter:brightness(1.08);transform:translateY(-2px)}
input{
 width:min(280px,90%);padding:15px;border-radius:18px;
 border:2px solid #ed8ac1;background:#ffffffd9;
 font-size:18px;text-align:center;outline:none
}
.card{
 width:min(480px,100%);margin:12px auto;padding:22px;
 border:1px solid #ffffffed;border-radius:25px;
 background:#ffffffc9;backdrop-filter:blur(12px);
 box-shadow:0 12px 35px #a54e9c20;
}
.entrance{animation:entrance .8s both}
@keyframes entrance{
 from{opacity:0;transform:translateY(35px) scale(.96)}
 to{opacity:1;transform:translateY(0) scale(1)}
}
.heart{font-size:65px;animation:heartbeat 1.4s infinite}
@keyframes heartbeat{50%{transform:scale(1.15)}}
.glow{animation:glow 2s infinite alternate}
@keyframes glow{to{text-shadow:0 0 22px #ff56b8}}
/* Floating balloons */
.sky{position:fixed;inset:0;overflow:hidden;pointer-events:none;z-index:0}
.balloon{
 position:absolute;bottom:-150px;width:38px;height:50px;
 border-radius:50% 50% 45% 45%;
 background:var(--balloon);opacity:.8;
 box-shadow:inset -6px -5px 10px #00000012;
 animation:floatUp var(--speed) linear infinite;
 animation-delay:var(--delay)
}
.balloon:before{
 content:"";position:absolute;bottom:-7px;left:15px;
 border-left:5px solid transparent;border-right:5px solid transparent;
 border-top:8px solid var(--balloon)
}
.balloon:after{
 content:"";position:absolute;top:55px;left:19px;
 height:70px;border-left:1px solid #ffffffa8
}
@keyframes floatUp{
 from{transform:translateY(0) rotate(-8deg)}
 to{transform:translateY(-125vh) rotate(12deg)}
}
.sparkle{position:fixed;pointer-events:none;z-index:3;animation:pop .9s forwards}
@keyframes pop{to{transform:translateY(-100px) rotate(100deg) scale(0);opacity:0}}
.message-card{
 text-align:left;cursor:pointer;border:2px solid #ffffff;
 transition:transform .3s,box-shadow .3s
}
.message-card:hover{transform:translateY(-4px);box-shadow:0 12px 30px #c25eab30}
.message-card h3{text-align:center;color:#a044d5}
.opened{animation:cardOpen .6s both}
@keyframes cardOpen{
 from{opacity:.4;transform:rotateX(12deg) scale(.97)}
 to{opacity:1;transform:rotateX(0) scale(1)}
}
.message{white-space:pre-line;line-height:1.9;font-size:16px}
.next{display:block;margin:18px auto 0}
#progress{font-weight:bold;color:#9b4baf}
#cakeArea{padding-top:35px}
.cake{position:relative;width:250px;height:180px;margin:35px auto 10px}
.tier{position:absolute;left:15px;width:220px;height:65px;border-radius:12px 12px 18px 18px}
.bottom{top:92px;background:linear-gradient(90deg,#a855d9,#e5a5ff,#a855d9);border-bottom:9px solid #8a42bd}
.middle{top:49px;background:linear-gradient(90deg,#ff8ab9,#ffd1e6,#ff8ab9);border-bottom:8px solid #e867a1}
.top{top:12px;height:48px;background:#fff0f8;border-radius:50% 50% 15px 15px/35% 35% 15px 15px;border-bottom:8px solid #f6a2c8;z-index:2}
.candle{
 position:absolute;top:-30px;width:11px;height:43px;z-index:4;
 border-radius:4px;background:repeating-linear-gradient(45deg,#fff 0 5px,#f36da5 5px 10px);
 cursor:pointer
}
.c1{left:65px}.c2{left:120px}.c3{left:175px}
.flame{
 position:absolute;top:-22px;left:-2px;width:15px;height:21px;
 background:#ffb32c;border-radius:50% 50% 50% 0;transform:rotate(-45deg);
 box-shadow:0 0 18px #ffad21;animation:flicker .5s infinite alternate
}
@keyframes flicker{to{transform:rotate(-35deg) scale(.8)}}
.off .flame{display:none}
#finalWish{animation:entrance 1.1s both}
.poem{font-style:italic;font-size:17px}
</style>
</head>
<body>

<div class="sky" id="sky"></div>

<!-- PASSWORD -->
<section id="login" class="screen">
 <div class="heart">💌</div>
 <h1 class="glow">A Secret Surprise</h1>
 <h2>Especially for Arjoo 🎀</h2>
 <div class="card entrance">
  <p>Someone has prepared a little world of happiness for you. 💗</p>
  <p>But the magic door needs a secret password! 🔐</p>
  <input id="pass" type="password" placeholder="Your secret password"
   inputmode="numeric" autocomplete="off">
  <br><button onclick="unlock()">Unlock My Surprise ✨</button>
  <p id="error" class="small"></p>
 </div>
 <p class="small">A little surprise, made with lots of wishes 🌷</p>
</section>

<!-- WELCOME -->
<section id="welcome" class="screen hidden">
 <div class="heart">🎈</div>
 <h1 class="glow">Happy Birthday, Arjoo!</h1>
 <div class="card entrance">
  <p>Today the world feels a little brighter, the stars seem a little closer, and every little celebration has one special name in it… <b>YOURS!</b> 💖</p>
  <p>I've hidden three messages here, each with something special I wanted to tell you.</p>
  <p>Ready to open them? 🌸</p>
 </div>
 <button onclick="go('messages')">Let's Begin! 💕</button>
</section>

<!-- MESSAGES -->
<section id="messages" class="screen hidden">
 <h1>Three Little Surprises 💌</h1>
 <p>Tap each colorful card and let it reveal its secret. 🦋</p>

 <div class="card message-card" onclick="openMsg(0)">
  <h3>🎂 Message One · Birthday Wishes</h3>
  <p id="m0">💗 Tap to open your birthday letter…</p>
 </div>

 <div class="card message-card" onclick="openMsg(1)">
  <h3>🌸 Message Two · A Little Compliment</h3>
  <p id="m1">✨ There's something I want you to know…</p>
 </div>

 <div class="card message-card" onclick="openMsg(2)">
  <h3>💘 Message Three · From My Heart</h3>
  <p id="m2">🦋 A poem written just for you…</p>
 </div>

 <p id="progress">Messages opened: 0 / 3 💖</p>
 <button id="gift" class="hidden" onclick="go('reveal')">🎁 Open Your Final Surprise</button>
</section>

<!-- REVEAL -->
<section id="reveal" class="screen hidden">
 <div class="heart">🎁</div>
 <h1 class="glow">You Found Every Message!</h1>
 <div class="card entrance">
  <p>Three little letters, a few honest words, and one final surprise still waiting for you… 💗</p>
  <p>Take a deep breath, make a wish, and get ready for the sweetest part! ✨</p>
 </div>
 <button onclick="go('cake')">Reveal the Birthday Cake! 🎂</button>
</section>

<!-- CAKE -->
<section id="cake" class="screen hidden">
 <h1>Surprise, Birthday Girl! 🎉</h1>
 <p>Your very own birthday cake is here, Arjoo! 💗</p>

 <div id="cakeArea">
  <div class="cake">
   <div class="candle c1" onclick="blow(this)"><span class="flame"></span></div>
   <div class="candle c2" onclick="blow(this)"><span class="flame"></span></div>
   <div class="candle c3" onclick="blow(this)"><span class="flame"></span></div>
   <div class="tier top"></div>
   <div class="tier middle"></div>
   <div class="tier bottom"></div>
  </div>
  <h2>🎂 HAPPY BIRTHDAY, ARJOO! 🎂</h2>
  <p>Close your eyes, make a wish, and blow out all three candles! 🌠</p>
  <p id="cstatus">🕯️ Candles still glowing: 3</p>
  <button onclick="blowAll()">Blow Out the Candles! 💨</button>
 </div>

 <div id="finalWish" class="card hidden">
  <div class="heart">🎉💖🎉</div>
  <h1 class="glow">HAPPY BIRTHDAY, ARJOO!</h1>
  <p>May every sunrise bring you hope, every sunset bring you peace, and every new day give you a reason to smile. 🌅</p>
  <p>May your dreams find their way to you, your hard work turn into success, and your life be filled with beautiful memories and people who truly care about you. 🌷</p>
  <p>Keep laughing that lovely laugh, keep chasing the things you love, and never forget that you deserve happiness in all its wonderful forms. 🦋</p>
  <h2>🎁 Have the most magical birthday ever! 🎁</h2>
  <p>And remember, this little surprise was made especially for you. 💌</p>
  <p><b>Once again, Happy Birthday, Arjoo! 🎂💗</b></p>
 </div>
</section>

<script>
// Animated balloons
const sky = document.getElementById("sky");
const colors = ["#ff69ad","#a77aff","#55c9ff","#ffc857","#ff8c79","#8cdebe"];
for(let i=0;i<19;i++){
 const b=document.createElement("div");
 b.className="balloon";
 b.style.left=(Math.random()*100)+"%";
 b.style.setProperty("--balloon",colors[i%colors.length]);
 b.style.setProperty("--speed",(9+Math.random()*13)+"s");
 b.style.setProperty("--delay",(-Math.random()*18)+"s");
 b.style.transform="scale("+(0.65+Math.random()*.7)+")";
 sky.appendChild(b);
}

function sparkle(){
 const e=document.createElement("span");
 e.className="sparkle";
 e.textContent=["💖","✨","🎉","🌸","💕"][Math.floor(Math.random()*5)];
 e.style.left=(10+Math.random()*80)+"vw";
 e.style.top=(15+Math.random()*65)+"vh";
 document.body.appendChild(e);
 setTimeout(()=>e.remove(),1000);
}
function celebrationSparks(){
 for(let i=0;i<22;i++)setTimeout(sparkle,i*100);
}

function unlock(){
 if(document.getElementById("pass").value==="2010"){
  go("welcome");celebrationSparks();
 }else{
  document.getElementById("error").textContent="Oops! Try the secret password again 💗";
 }
}
document.getElementById("pass").addEventListener("keydown",e=>{
 if(e.key==="Enter")unlock();
});

function go(id){
 document.querySelectorAll(".screen").forEach(s=>s.classList.add("hidden"));
 const target=document.getElementById(id);
 target.classList.remove("hidden");
 target.classList.remove("entrance");
 void target.offsetWidth;
 target.classList.add("entrance");
 window.scrollTo({top:0,behavior:"smooth"});
 if(id==="reveal")celebrationSparks();
}

// Each message is revealed only when tapped
const letters=[
`🎂 HAPPY BIRTHDAY, ARJOO! 🎂💖

Today isn't just another date on the calendar; it's a day worth celebrating because it's the day someone as wonderful as you came into this world. And honestly, that deserves all the balloons, cake, flowers, and happiness imaginable! 🎈🌸

I hope this new chapter of your life brings you moments that make you laugh until your cheeks hurt, friends who make every memory unforgettable, and opportunities that take you closer to all your dreams.

May the little things bring you the biggest smiles. May your worries become lighter, your confidence grow stronger, and your heart always find reasons to feel grateful.

I hope you get everything you've been wishing for, even the dreams you haven't told anyone about yet. May you keep discovering new things, learning, growing, and becoming an even more amazing version of yourself.

You deserve a birthday full of surprises, your favourite treats, genuine smiles, and people who remind you how much you matter.

So today, forget the ordinary for a while. Enjoy every moment, take lots of pictures, eat that extra slice of cake, and make memories you'll look back on with a smile! 🎂✨

Here's to a year filled with adventures, achievements, peaceful nights, exciting mornings, and a thousand beautiful reasons to smile.

HAPPY BIRTHDAY ONCE AGAIN, ARJOO! 💗🎉
May your world always have a little extra magic. 🦋`,

`🌸 SOMETHING I WANT YOU TO KNOW… 🌸💗

Arjoo, have you ever noticed how some people have a way of making things feel a little more special without even trying? That's the kind of beauty I see in you.

Of course, you're pretty, and your smile is genuinely lovely. But to me, there's more to it than just appearance. It's the little things, the way you express yourself, the way you laugh, and all those small details that make you uniquely YOU. ✨

You have a kind of charm that is difficult to explain in a single sentence. Sometimes, a person can look beautiful in a picture, but the impression they leave in someone's heart is something even more special.

And that's what makes you stand out to me. You don't have to compete with anyone, pretend to be someone else, or try too hard to impress people. Being yourself is already something worth appreciating. 🌷

If I could give you one birthday gift that lasted longer than a day, it would be the ability to see yourself through the eyes of the people who genuinely appreciate you.

I hope you always remember your worth, keep your beautiful individuality, and never let a difficult day make you forget all the good things about yourself.

So yes, Arjoo, I think you're really beautiful. But the sweetest part is that my appreciation for you isn't limited to how you look. It's the person you are, too. 💖

Never stop smiling, birthday girl. The world needs more of your sparkle! 🌟🦋`,

`💌 A POEM FROM MY HEART TO YOURS 💌

If stars could write, they'd spell your name,
And every night would glow the same.
The moon would smile, the skies turn blue,
As if the world were made for you.

Your laugh could brighten rainy skies,
There's something lovely in your eyes.
And when the day feels dull and grey,
Your thought could chase the clouds away.

If I could gift you endless skies,
I'd fill them up with butterflies.
A thousand wishes, wrapped in gold,
And little stories yet untold.

I'd wish you courage for each climb,
And happiness through changing time.
A hand to hold when days are long,
A heart that cheers when things go wrong.

But poems can only say so much,
And words can never quite replace
The simple joy of talking to you,
Or seeing happiness on your face.

So let me leave the sweetest line,
A little question, yours and mine.
No riddles, hints, or hidden clue,
I'm saying what I feel to you:

ARJOO, you are really someone anyone would want and i am one of those.💗

never stop to smile, never forget who you are.🌹💖

And at last i want to say that please listen to me not as a girl but as a friend, don't threat me like before🙂, 
because you are someone i don't want to hear that from you.And please listen, listen the effort i done and i want to make in future.If you like it then text the feedback on my main account of Insta😶.Bhot dam laga ke likha hai padhne ke baad mujhe kuch ulta seedha bol mat dena please🙏🏻, kyunki bhot mehnat lagi hai isse banane mein.`
];

const opened=[false,false,false];

function openMsg(i){
 if(opened[i])return;
 opened[i]=true;
 const el=document.getElementById("m"+i);
 el.textContent=letters[i];
 el.classList.add("message","opened");
 document.getElementById("progress").textContent=
 "Messages opened: "+opened.filter(Boolean).length+" / 3 💖";
 celebrationSparks();
 if(opened.every(Boolean)){
  document.getElementById("gift").classList.remove("hidden");
  document.getElementById("progress").textContent=
  "✨ All three messages unlocked! Your final surprise is ready! 🎁";
 }
}

let extinguished=0;
function blow(c){
 if(c.classList.contains("off"))return;
 c.classList.add("off");
 extinguished++;
 updateCake();
}
function blowAll(){
 document.querySelectorAll(".candle").forEach(c=>{
  if(!c.classList.contains("off")){
   c.classList.add("off");
   extinguished++;
  }
 });
 updateCake();
}
function updateCake(){
 const remaining=3-extinguished;
 document.getElementById("cstatus").textContent=
 remaining>0
 ? "🕯️ Candles still glowing: "+remaining
 : "💨 Wish made! All the candles are out! 🎉";
 if(remaining===0){
  document.getElementById("finalWish").classList.remove("hidden");
  celebrationSparks();
  setTimeout(celebrationSparks,700);
  document.getElementById("finalWish").scrollIntoView({behavior:"smooth",block:"start"});
 }
}
</script>
</body>
</html>
