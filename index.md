---
title: Smoky Jazz Jam Home
layout: default
---
<style>
.larger-text {
  font-size: 20px;
}
.image-container {
  position: relative;
  text-align: center;
  display: inline-block;
  width: 100%;
  max-width: 800px;
}
.image-container img {
  width: 100%;
  height: auto;
  max-width: 100%;
}
.main-title {
  position: absolute;
  top: 15px;
  left: 50%;
  transform: translateX(-50%);
  color: #2c3e50;
  font-size: 28px;
  font-weight: bold;
  text-shadow: 2px 2px 4px rgba(255, 255, 255, 0.8);
  letter-spacing: 1px;
  text-align: center;
  width: 90%;
}
.overlay-text {
  position: absolute;
  top: 60px;
  left: 50%;
  transform: translateX(-50%);
  background-color: rgba(0, 0, 0, 0.7);
  color: white;
  padding: 10px 15px;
  border-radius: 8px;
  font-size: 14px;
  font-weight: bold;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
  text-align: center;
  width: 80%;
  max-width: 250px;
}

/* Mobile-specific styles */
@media screen and (max-width: 768px) {
  .main-title {
    font-size: 20px;
    top: 10px;
    letter-spacing: 0.5px;
  }
  
  .overlay-text {
    font-size: 12px;
    top: 40px;
    padding: 8px 12px;
    width: 85%;
  }
  
  .larger-text {
    font-size: 18px;
  }
  
  .content-container {
    max-width: 95% !important;
    padding: 0 10px !important;
  }
}

.content-container {
  max-width: 800px;
  margin: 0 auto;
}
</style>

<div style="text-align: center;">
  <div class="image-container">
    <img src="misty_forest.jpg" alt="Description" />
    <div class="main-title">
      Smoky Mountain Jazz Jam
    </div>
    <div class="overlay-text">
      Next Jam Session<br>
      To Be Announced<br>
      Time of jam here
    </div>
  </div>
</div>
<br>
<br>

<div class="content-container">
  <h1><strong>About The Smoky Mountain Jazz Jam</strong></h1>

  <ul class="larger-text">
    <li>The Smoky Mountain Jazz Jam is a new monthly jazz jam session being held at the Folkmoot Center of the Arts in Waynesville, NC.</li>
    <li>The jam focuses primarily on playing songs from the Great American Songbook and by great jazz composers.</li>
    <li>A partial list of songs that will be played at each monthly jam session will be posted in advance and can be found here: <a href="jam_tunes">Jam Session Song List</a></li>
    <li>Some frequently asked questions are addressed here: <a href="faq">FAQ</a></li>
  </ul>

  <h2><strong>Where</strong></h2>

  <ul class="larger-text">
    <li><a href="https://www.folkmoot.org/">Folkmoot Center for the Arts</a> in Waynesville, NC</li>
    <li>Address: <a href="https://maps.app.goo.gl/KduAxvnix88e4M369">Building B, 1122 Virginia Avenue, Waynesville, NC</a></li>
    <li>The jam will take place in the Folkmoot auditorium.</li>
  </ul>

  <h2><strong>When</strong></h2>

  <ul class="larger-text">
    <li>Jam sessions will be held on the ... (recurring day of month/week)</li>
    <li>The next jam session will be announced soon.</li>
  </ul>

  <h2><strong>Contact</strong></h2>
  <ul class="larger-text">
    <li>smokyjazzjam@gmail.com</li>
  </ul>
</div>
