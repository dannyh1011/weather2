<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>雙天氣小工具顯示</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      width: 100%;
      background-color: #2e2e2e; /* 深灰背景 */
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .widget-container {
      margin: 20px 0; /* 上下間距 */
    }
  </style>
</head>
<body>
  <div class="widget-container">
    <div id="ww_8e62d423d5a28" v='1.3' loc='id' a='{"t":"horizontal","lang":"zh-Hant","sl_lpl":1,"ids":["wl9238"],"font":"Arial","sl_ics":"one_a","sl_sot":"celsius","cl_bkg":"#2e2e2e","cl_font":"#FFFFFF","cl_cloud":"#FFFFFF","cl_persp":"#81D4FA","cl_sun":"#FFC107","cl_moon":"#FFC107","cl_thund":"#FF5722"}'>
      <a href="https://weatherwidget.org/" id="ww_8e62d423d5a28_u" target="_blank">Weather widget for website</a>
    </div>
  </div>

  <div class="widget-container">
    <div id="ww_4a37cd6b892e8" v='1.3' loc='id' a='{"t":"responsive","lang":"zh-Hant","sl_lpl":1,"ids":["wl9238"],"font":"Arial","sl_ics":"one_a","sl_sot":"celsius","cl_bkg":"#2e2e2e","cl_font":"#FFFFFF","cl_cloud":"#FFFFFF","cl_persp":"#81D4FA","cl_sun":"#FFC107","cl_moon":"#FFC107","cl_thund":"#FF5722","cl_odd":"#0000000a"}'>
      <a href="https://weatherwidget.org/" id="ww_4a37cd6b892e8_u" target="_blank">Weather widget for website</a>
    </div>
  </div>

  <!-- 載入兩個 widget script -->
  <script async src="https://app3.weatherwidget.org/js/?id=ww_8e62d423d5a28"></script>
  <script async src="https://app3.weatherwidget.org/js/?id=ww_4a37cd6b892e8"></script>
</body>
</html>
