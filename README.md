# ICT-PROJECT
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Bayola, Justin Gabriel - ICT</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", Arial, sans-serif;
  background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
  color: #ffffff;
}

/* HEADER */
header {
  text-align: center;
  padding: 70px 20px;
  animation: fadeDown 1.5s ease;
}

header h1 {
  font-size: 42px;
  letter-spacing: 4px;
}

header p {
  margin-top: 10px;
  opacity: 0.85;
  font-size: 16px;
}

/* CARD STYLE */
.card {
  width: 85%;
  max-width: 900px;
  margin: 40px auto;
  padding: 30px;
  background: rgba(255,255,255,0.12);
  backdrop-filter: blur(12px);
  border-radius: 18px;
  box-shadow: 0 15px 40px rgba(0,0,0,0.45);
  animation: fadeUp 1.4s ease;
}

.card h2 {
  text-align: center;
  margin-bottom: 15px;
  letter-spacing: 2px;
}

.card p {
  text-align: center;
  line-height: 1.8;
  font-size: 15px;
  opacity: 0.95;
}

/* GALLERY */
.gallery {
  display: flex;
  justify-content: center;
  gap: 25px;
  margin-top: 20px;
  flex-wrap: wrap;
}

.gallery img {
  width: 260px;
  border-radius: 15px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.6);
  transition: transform 0.4s;
}

.gallery img:hover {
  transform: scale(1.08);
}

/* VIDEO */
video {
  display: block;
  margin: 20px auto 0;
  width: 65%;
  border-radius: 15px;
  box-shadow: 0 15px 35px rgba(0,0,0,0.7);
}

/* FOOTER */
footer {
  text-align: center;
  padding: 25px;
  font-size: 30px;
  opacity: 0.7;
}

/* ANIMATIONS */
@keyframes fadeDown {
  from { opacity: 0; transform: translateY(-40px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes fadeUp {
  from { opacity: 0; transform: translateY(60px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>

</head>
<body>

<header>
  <h1>4TH YEAR STUDENT</h1>
  <p>Focused • Determined • Ready for the Future</p>
</header>

<div class="card">
  <h2>About Me</h2>
  <p>
    I am Justin Gabriel W. Bayola, 21 Years Old, From Antipolo city. 
   My Hobbies is I enjoy capturing moments, listening to music, and watching videos.
I believe that success comes from consistency and dedication.
  </p>
</div>

<div class="card">
  <h2>Favorite Song</h2>
  <p><b>
Sanctuary</b> – Song by Joji</p>
  <p>
   Go ahead and bark after dark
Fallen star, I'm your one call away
Motel halls, neon walls
When night falls, I am your escape
When you lay alone, I ache
Something I wanted to feel
If you've been waiting for fallin' in love
Babe, you don't have to wait on me
'Cause I've been aiming for heaven above
But an angel ain't what I need
Not anyone, you're the one
More than fun, you're the sanctuary
  </p>
</div>

<div class="card">
  <h2>Photo</h2>
  <div class="gallery">
    <img src="pic1.jpg" alt="My Photo 1">
    <img src="pic2.jpg" alt="My Photo 2">
  </div>
</div>

<div class="card">
  <h2>Video</h2>
  <video controls>
    <source src="myvideo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<footer>
  Name: Bayola, Justin Gabriel W. -  Yr/Sec: BIT 4-N FSM
</footer>

</body>
</html>
