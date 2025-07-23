<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no" />
  <title>全螢幕偏左天氣展示</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      background: black;
      display: flex;
      justify-content: flex-start; /* 由置中改為左對齊 */
      align-items: center;
      padding-left: 5vw; /* 左側內距，可依需求調整 */
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
      width: 90vw;
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
    <div class="divider"></div>

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

    <div class="divider"></div>

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

  <script defer src="https://app3.weatherwidget.org/js/?id=ww_03524cc90608a"></script>
  <script defer src="https://app3.weatherwidget.org/js/?id=ww_04509b4286730"></script>

</body>
</html>
