<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no" />
  <title>全螢幕天氣展示（最終校正版本）</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      background: black;
      display: flex;
      justify-content: center;  /* 水平置中 */
      align-items: center;      /* 垂直置中 */
      box-sizing: border-box;
    }

    *, *::before, *::after {
      box-sizing: inherit;
    }

    .container {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      width: 85vw;        /* 適中寬度，避免太寬視覺偏右 */
      max-width: 1200px;
    }

    .widget {
      width: 100%;
      max-width: 100%;
    }

    .divider {
      width: 100%;
      height: 2px;
      background: #ffffff;
      margin: 30px 0;
    }

    a[id$="_u"] {
      display: none !important;
    }

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

    <!-- 上方 weather widget -->
    <div class="widget" id="ww_03524cc90608a" v='1.3' loc='id'
      a='{
        "t":"horizontal",
        "lang":"en",
        "sl_lpl":1,
        "ids":["wl9238"],
        "font":"Arial",
        "sl_ics":"one_a",
        "sl_sot":"celsius",
        "cl_bkg":"image",
        "cl_font":"#FFFFFF",
        "cl_cloud":"#FFFFFF",
        "cl_persp":"#81D4FA",
        "cl_sun":"#FFC107",
        "cl_moon":"#FFC107",
        "cl_thund":"#FF5722"
      }'>
      <a href="https://weatherwidget.org/" id="ww_03524cc90608a_u" target="_blank">Free weather widget</a>
    </div>

    <!-- 中間白線 -->
    <div class="divider"></div>

    <!-- 下方 weather widget -->
    <div class="widget" id="ww_04509b4286730" v='1.3' loc='id'
      a='{
        "t":"responsive",
        "lang":"en",
        "sl_lpl":1,
        "ids":["wl9238"],
        "font":"Arial",
        "sl_ics":"one_a",
        "sl_sot":"celsius",
        "cl_bkg":"image",
        "cl_font":"#FFFFFF",
        "cl_cloud":"#FFFFFF",
        "cl_persp":"#81D4FA",
        "cl_sun":"#FFC107",
        "cl_moon":"#FFC107",
        "cl_thund":"#FF5722"
      }'>
      <a href="https://weatherwidget.org/" id="ww_04509b4286730_u" target="_blank">Free weather widget</a>
    </div>
  </div>

  <!-- widget scripts -->
  <script defer src="https://app3.weatherwidget.org/js/?id=ww_03524cc90608a"></script>
  <script defer src="https://app3.weatherwidget.org/js/?id=ww_04509b4286730"></script>

</body>
</html>

