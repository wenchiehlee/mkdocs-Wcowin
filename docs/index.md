---
hide:
  #- navigation # 顯示右
  #- toc #顯示左
  - footer
  - feedback
comments: false
---
<!--
██╗    ██╗ ██████╗ ██████╗ ██╗    ██╗██╗███╗   ██╗
██║    ██║██╔════╝██╔═══██╗██║    ██║██║████╗  ██║
██║ █╗ ██║██║     ██║   ██║██║ █╗ ██║██║██╔██╗ ██║
██║███╗██║██║     ██║   ██║██║███╗██║██║██║╚██╗██║
╚███╔███╔╝╚██████╗╚██████╔╝╚███╔███╔╝██║██║ ╚████║
 ╚══╝╚══╝  ╚═════╝ ╚═════╝  ╚══╝╚══╝ ╚═╝╚═╝  ╚═══╝
                                                  


____    __    ____  ______   ______   ____    __    ____  __  .__   __. 
\   \  /  \  /   / /      | /  __  \  \   \  /  \  /   / |  | |  \ |  | 
 \   \/    \/   / |  ,----'|  |  |  |  \   \/    \/   /  |  | |   \|  | 
  \            /  |  |     |  |  |  |   \            /   |  | |  . `  | 
   \    /\    /   |  `----.|  `--'  |    \    /\    /    |  | |  |\   | 
    \__/  \__/     \______| \______/      \__/  \__/     |__| |__| \__| 

 __        __                _       
 \ \      / /__ _____      _(_)_ __  
  \ \ /\ / / __/ _ \ \ /\ / / | '_ \ 
   \ V  V / (_| (_) \ V  V /| | | | |
    \_/\_/ \___\___/ \_/\_/ |_|_| |_|
                                     
 ___       ___     ____     ____     ___       ___    _____      __      _  
(  (       )  )   / ___)   / __ \   (  (       )  )  (_   _)    /  \    / ) 
 \  \  _  /  /   / /      / /  \ \   \  \  _  /  /     | |     / /\ \  / /  
  \  \/ \/  /   ( (      ( ()  () )   \  \/ \/  /      | |     ) ) ) ) ) )  
   )   _   (    ( (      ( ()  () )    )   _   (       | |    ( ( ( ( ( (   
   \  ( )  /     \ \___   \ \__/ /     \  ( )  /      _| |__  / /  \ \/ /   
    \_/ \_/       \____)   \____/       \_/ \_/      /_____( (_/    \__/    
                                                                            


-->
                                   

<!-- <center><font  color= #518FC1 size=6 class="ml3">Mkdocs-Wcowin部落格主題</font></center>
<script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script> -->



<!-- <center>
<font  color= #608DBD size=3>
<span id="jinrishici-sentence">正在載入今日詩詞....</span>
<script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>
</font>
</center> -->


<!-- 可選一言 -->
<!-- <center>
<font  color= #608DBD size=3>
<p id="hitokoto">
  <a href="#" id="hitokoto_text" target="_blank"></a>
</p>
<script>
  fetch('https://v1.hitokoto.cn')
    .then(response => response.json())
    .then(data => {
      const hitokoto = document.querySelector('#hitokoto_text')
      hitokoto.href = `https://hitokoto.cn/?uuid=${data.uuid}`
      hitokoto.innerText = data.hitokoto
    })
    .catch(console.error)
</script>
</font>
</center> -->


<div id="rcorners2" >
  <div id="rcorners1">
    <!-- <i class="fa fa-calendar" style="font-size:100"></i> -->
    <body>
      <font color="#4351AF">
        <p class="p1"></p>
<script defer>
    //格式：2020年04月12日 10:20:00 星期二
    function format(newDate) {
        var day = newDate.getDay();
        var y = newDate.getFullYear();
        var m =
            newDate.getMonth() + 1 < 10
                ? "0" + (newDate.getMonth() + 1)
                : newDate.getMonth() + 1;
        var d =
            newDate.getDate() < 10 ? "0" + newDate.getDate() : newDate.getDate();
        var h =
            newDate.getHours() < 10 ? "0" + newDate.getHours() : newDate.getHours();
        var min =
            newDate.getMinutes() < 10
                ? "0" + newDate.getMinutes()
                : newDate.getMinutes();
        var s =
            newDate.getSeconds() < 10
                ? "0" + newDate.getSeconds()
                : newDate.getSeconds();
        var dict = {
            1: "一",
            2: "二",
            3: "三",
            4: "四",
            5: "五",
            6: "六",
            0: "天",
        };
        //var week=["日","一","二","三","四","五","六"]
        return (
            y +
            "年" +
            m +
            "月" +
            d +
            "日" +
            " " +
            h +
            ":" +
            min +
            ":" +
            s +
            " 星期" +
            dict[day]
        );
    }
    var timerId = setInterval(function () {
        var newDate = new Date();
        var p1 = document.querySelector(".p1");
        if (p1) {
            p1.textContent = format(newDate);
        }
    }, 1000);
</script>
      </font>
    </body>
    <!-- <b><span id="time"></span></b> -->
  </div>
  <ul>
    <li>透過主題和目錄以開啟文章</li>
    <ul>
      <li>基於Material for MkDocs美化</li>
      <li>簡潔美觀，功能多元化</li>
    </ul>
    <li>簡單易上手，小白配置</li>
    <li>
      如遇到網頁卡頓的情況，請使用<strong><a href="https://www.yuque.com/wcowin/mkdocs-wcowin?# 《Mkdocs-Wcowin中文教程》" target="_blank">Mkdocs-Wcowin中文教程(語雀)</a></strong>
    </li>
  </ul>
</div> 

<!-- - 基於Material for MkDocs美化
- 簡潔美觀，功能多元化
- 簡單易上手，小白配置
- 𝕙𝕒𝕧𝕖 𝕒 𝕘𝕠𝕠𝕕 𝕥𝕚𝕞𝕖 ! -->

快速談話(1) 聯絡我(2)
{ .annotate }

1. Test
2. 18939533255
***  

<!-- <strong>推薦文章:material-book:</strong>

  - [利用Mkdocs部署靜態網頁至GitHub pages](blog/Mkdocs/mkdocs1.md)
  - [Mkdocs部署配置說明(mkdocs.yml)](blog/Mkdocs/mkdocs2.md)
  - [如何給MKdocs新增友鏈](blog/websitebeauty/linktech.md)
  - [網站新增Mkdocs部落格](blog/Mkdocs/mkdocsblog.md)
  - [Blogger](blog/index.md) -->



<div class="grid cards" markdown>

-   :simple-materialformkdocs:{ .lg .middle } __Mkdocs教程__

    ---

    - [利用Mkdocs部署靜態網頁至GitHub pages](blog/Mkdocs/mkdocs1.md)
    - [Mkdocs部署配置說明(mkdocs.yml)](blog/Mkdocs/mkdocs2.md)
    - [如何給MKdocs新增友鏈](blog/websitebeauty/linktech.md)
    - [網站新增Mkdocs部落格](blog/Mkdocs/mkdocsblog.md)
    - [Blogger](blog/index.md)


-   :simple-aboutdotme:{ .lg .middle } __關於__

    ---
    - [Mkdocs-Wcowin部落格主題社群](https://support.qq.com/products/646913/){target=“_blank”}
    - [留言板](liuyanban.md)[^Knowing-that-loving-you-has-no-ending] 
    - [Blogger](blog/index.md)   
    [:octicons-arrow-right-24: 瞭解我](about/geren.md)[^see-how-much-I-love-you]

</div>



[^Knowing-that-loving-you-has-no-ending]:太陽總是能溫暖向日葵  
[^see-how-much-I-love-you]:All-problems-in-computer-science-can-be-solved-by-another-level-of-indirection

   <body>
        <font color="#B9B9B9">
        <p style="text-align: center; ">
                <span>本站已經執行</span>
                <span id='box1'></span>
    </p>
      <div id="box1"></div>
      <script>
        function timingTime(){
          let start = '2024-11-01 00:00:00'
          let startTime = new Date(start).getTime()
          let currentTime = new Date().getTime()
          let difference = currentTime - startTime
          let m =  Math.floor(difference / (1000))
          let mm = m % 60  // 秒
          let f = Math.floor(m / 60)
          let ff = f % 60 // 分鐘
          let s = Math.floor(f/ 60) // 小時
          let ss = s % 24
          let day = Math.floor(s  / 24 ) // 天數
          return day + "天" + ss + "時" + ff + "分" + mm +'秒'
        }
        setInterval(()=>{
          document.getElementById('box1').innerHTML = timingTime()
        },1000)
      </script>
      </font>
    </body>


<!-- <script src="//code.tidio.co/6jmawe9m5wy4ahvlhub2riyrnujz7xxi.js" async></script>
 -->

