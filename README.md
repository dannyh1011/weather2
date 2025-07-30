<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>全螢幕置中天氣展示</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      background: #2e2e2e;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .container {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      width: 90vw;
      max-width: 1200px;
    }

    .widget {
      width: 100%;
      max-width: 100%;
    }

    .divider {
      width: 100%;        /* 與 widget 寬度一致 */
      height: 2px;        /* 白線粗細一致 */
      background: #ffffff; /* 白色線條 */
      margin: 30px 0;     /* 上下間距 */
    }

    /* 隱藏 weather2 標題與下方白線，如在 HTML 中 */
    h1, hr {
      display: none !important;
    }

    /* 隱藏 widget branding link */
    a[id$="_u"] {
      display: none !important;
    }

    /* 移除 widget 內部底線、邊框、陰影，如有 */
    .widget * {
      border-bottom: none !important;
      box-shadow: none !important;
    }

    .widget iframe {
      border: none !important;
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- 上方白線 -->
    <div class="divider"></div>

    <!-- 橫向 weather widget -->
    <div class="widget" id="ww_a728af039000a" v='1.3' loc='id'
      a='{
        "t":"horizontal",
        "lang":"en",
        "sl_lpl":1,
        "ids":[],
        "font":"Arial",
        "sl_ics":"one_a",
        "sl_sot":"celsius",
        "cl_bkg":"#2e2e2e",
        "cl_font":"#FFFFFF",
        "cl_cloud":"#FFFFFF",
        "cl_persp":"#81D4FA",
        "cl_sun":"#FFC107",
        "cl_moon":"#FFC107",
        "cl_thund":"#FF5722"
      }'>
      <a href="https://weatherwidget.org/" id="ww_a728af039000a_u" target="_blank">Free weather widget</a>
    </div>

    <!-- 中間白線 -->
    <div class="divider"></div>

    <!-- 響應式 weather widget -->
    <div class="widget" id="ww_ac90862dca38f" v='1.3' loc='id'
      a='{
        "t":"responsive",
        "lang":"en",
        "sl_lpl":1,
        "ids":["wl9238"],
        "font":"Arial",
        "sl_ics":"one_a",
        "sl_sot":"celsius",
        "cl_bkg":"#2e2e2e",
        "cl_font":"#FFFFFF",
        "cl_cloud":"#FFFFFF",
        "cl_persp":"#81D4FA",
        "cl_sun":"#FFC107",
        "cl_moon":"#FFC107",
        "cl_thund":"#FF5722",
        "cl_odd":"#0000000a"
      }'>
      <a href="https://weatherwidget.org/" id="ww_ac90862dca38f_u" target="_blank">Free weather widget</a>
    </div>
  </div>

  <!-- widget scripts -->
  <script async src="https://app3.weatherwidget.org/js/?id=ww_a728af039000a"></script>
  <script async src="https://app3.weatherwidget.org/js/?id=ww_ac90862dca38f"></script>

</body>
</html>
