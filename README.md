<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Traffic to Airports from Sol Hotel</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      background-color: black;
      font-family: sans-serif;
    }
    .container {
      display: flex;
      height: 100vh;
    }
    .map {
      flex: 1;
      position: relative;
    }
    iframe {
      width: 100%;
      height: 100%;
      border: none;
    }
    .label {
      position: absolute;
      top: 10px;
      left: 10px;
      background-color: rgba(255,255,255,0.85);
      padding: 8px 16px;
      font-size: 20px;
      font-weight: bold;
      border-radius: 8px;
      z-index: 10;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- 桃園機場 -->
    <div class="map">
      <div class="label">Taoyuan International Airport</div>
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d3623.1721563900054!2d120.96693737559424!3d24.800753650167996!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e0!4m5!1s0x3468358a34fcfd0b%3A0x2b82b33495f0ccf!2zU29sIEhvdGVs!3m2!1d24.80165!2d120.9692!4m5!1s0x34681c4e8988bdc5%3A0xf2e37b987a528f91!2zVGFveXVhbiBJbnRlcm5hdGlvbmFsIEFpcnBvcnQ!3m2!1d25.077083!2d121.23241!5e0!3m2!1sen!2stw!4v1721978052609"
        allowfullscreen
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade">
      </iframe>
    </div>
<br>
    <!-- 松山機場 -->
    <div class="map">
      <div class="label">Songshan Airport</div>
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d3623.1721563900054!2d120.96693737559424!3d24.800753650167996!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e0!4m5!1s0x3468358a34fcfd0b%3A0x2b82b33495f0ccf!2zU29sIEhvdGVs!3m2!1d24.80165!2d120.9692!4m5!1s0x3442a974cc125e7f%3A0x1ed08a48f2e47c36!2zU29uZ3NoYW4gQWlycG9ydA!3m2!1d25.069815!2d121.552828!5e0!3m2!1sen!2stw!4v1721980000000"
        allowfullscreen
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade">
      </iframe>
    </div>
  </div>
</body>
</html>
    window.onload = showTaoyuan;
  </script>
</body>
</html>
