<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>影片播放</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      background-color: black;
      overflow: hidden;
    }
    video {
      position: absolute;
      top: 50%;
      left: 50%;
      min-width: 100%;
      min-height: 100%;
      transform: translate(-50%, -50%);
      object-fit: cover;
    }
  </style>
</head>
<body>
  <video autoplay muted loop playsinline>
    <source src="video.mp4" type="video/mp4">
    您的瀏覽器不支援影片播放
  </video>
</body>
</html>
