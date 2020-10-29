# WEB_1027_jQuery_GoTo

# 範例網站
https://kid421.github.io/Web_HC_ZL_jQuery_GoTo/

# CDN
放在 body 結束元素的上方，必須按造下方的順序
ˋˋˋ
<!-- jQuery CDN -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- 前往元素 js -->
<script src="https://github.com/KID421/Web_HC_ZL_jQuery_GoTo/blob/main/goTo.js"></script>

```

# 添加ID
在要前往的元素上添加ID

ˋˋ
<section id="box1"></section>
ˋˋˋ

# 屬性說明
屬性明稱           |屬性說明
--------------------|-------------------------
data-gt-target      |要前往的目標元素，必須使用ID
data-gt-duration    |持續時間，單位為毫秒
data-gt-offset      |位移，往上位移的值