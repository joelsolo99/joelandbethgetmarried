---
layout: page
permalink: /
---

<div class="container">
  <div class="logo">
    <h1>Joel & Beth</h1>
    <h2>get married!</h2>
  </div>

  <div class="info-box">
    <p class="date">17th August 2025</p>
    <p>We're looking forward to seeing you on our special day.<br>
    Please RSVP to let us know if you're <br>
    coming & what your dietary restrictions are.</p>
    <p>Feel free to browse this website for useful information. We hope to see you soon!</p>
  </div>
</div>

<style>
  body {
    font-family: 'Arial', sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 20px;
    color: #404040;
  }
  .container {
    max-width: 900px;
    margin: 0 auto;
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  .logo {
    text-align: center;
    margin-bottom: 20px;
    position: relative;
  }
  .logo h1 {
    font-size: 4em;
    color: #008080;
    margin: 0;
    font-weight: bold;
    display: inline-block;
    position: relative;
  }
  .logo h2 {
    font-size: 2em;
    color: #008080;
    margin: 0;
    font-weight: lighter;
  }
  /* Swirl patterns for the logo */
  .logo:before, .logo:after {
    content: '';
    position: absolute;
    top: 50%;
    width: 70px;
    height: 50px;
    background: url('https://cdn.pixabay.com/photo/2012/04/11/17/30/swirls-28868_960_720.png') no-repeat center;
    background-size: contain;
    transform: translateY(-50%);
  }
  .logo:before {
    left: -90px;
  }
  .logo:after {
    right: -90px;
  }
  .info-box {
    background-color: #008080;
    color: #f0f0f0;
    padding: 20px;
    border-radius: 8px;
    text-align: center;
    margin-bottom: 20px;
    font-size: 1.2em;
  }
  .info-box p {
    color: #404040;
    margin: 10px 0;
    line-height: 1.6;
  }
  .info-box .date {
    font-size: 2.5em;
    color: #f0f0f0;
    margin-bottom: 10px;
  }
</style>
