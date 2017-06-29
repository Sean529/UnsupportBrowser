<template>
    <div id="container">
        <h1>升级浏览器，升级你的浏览体验</h1>
        <div class="browsers">
            <ul>
                <li>
                    <a class="clearfix" href="https://www.google.com/chrome/browser/" target="_blank">
                        <img src="../assets/Chrome.png" alt="Download Chrome">
                        <p>Chrome</p>
                    </a>
                </li>
                <li>
                    <a class="clearfix" href="http://www.firefox.com.cn/" target="_blank">
                        <img src="../assets/FireFox.png" alt="Download Firefox">
                        <p>Firefox</p>
                    </a>
                </li>
                <li>
                    <a class="clearfix" href="http://www.apple.com/cn/safari/" target="_blank">
                        <img src="../assets/Safari.png" alt="Download Safari">
                        <p>Safari</p>
                    </a>
                </li>
                <li>
                    <a class="clearfix" href="http://www.opera.com/zh-cn" target="_blank">
                        <img src="../assets/opera.png" alt="Download Opera">
                        <p>Opera</p>
                    </a>
                </li>
            </ul>
        </div>
        <div class="suggestion">
            <ul>
                <li class="li-left">
                    <img src="../assets/gesture.png" alt="smily suggestion">
                </li>
                <li class="li-right">
                    <p>您的浏览器好像有点过时了。</p>
                    <p>为了您正常使用 本网站，建议安装以上现代浏览器。</p>
                </li>
            </ul>
        </div>
        <div class="footer">
            <img src="../assets/laugh.png" alt="laugh">
            <p>Copyright&nbsp;&nbsp;&copy;&nbsp;&nbsp;2017&nbsp;&nbsp;xiesz.com </p>
        </div>
    </div>
</template>
<script>

</script>
<style>
@charset "utf-8";
body,
div,
h1,
li,
p,
ul {
    padding: 0;
    margin: 0
}

img {
    border: 0
}

ul {
    list-style: none
}

h1 {
    font-weight: 400;
    font-size: 100%
}


.clearfix:after {
    content: ".";
    display: block;
    height: 0;
    clear: both;
    visibility: hidden
}

* html .clearfix {
    height: 1%
}

.clearfix {
    display: block
}

body {
    -webkit-font-smoothing: antialiased;
    font-family: "PingFang SC", "Helvetica Neue", "Hiragino Sans GB", "Segoe UI", "Microsoft YaHei", "微软雅黑", sans-serif;
    position: absolute;
    background-color: #F7F6F2;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0
}

#container {
    background: #F7F6F2;
    height: 100%;
    width: 100%;
    min-width: 900px;
    position: absolute
}

#container h1 {
    font-family: '黑体';
    text-align: center;
    font-weight: 400;
    padding: 2em 0 1.5em;
    font-size: 36px
}

#container div.browsers {
    height: 170px;
    width: 900px;
    margin: 0 auto 100px
}

#container div.browsers ul {
    display: block;
    width: 100%;
}

#container div.browsers ul li {
    text-align: center;
    width: 24.6%;
    display: inline-block;
}

#container div.browsers ul a {
    color: #000;
    border-radius: 5px;
    padding-bottom: 10px
}

#container div.browsers ul a:hover {
    color: #444;
    background: #F1F1F1
}

#container div.browsers ul img {
    width: 120px;
    margin-bottom: 10px
}

#container .suggestion {
    height: auto;
    width: 100%;
    background: #FFF;
    padding: 60px 0
}

#container .suggestion ul {
    height: 180px;
    width: 900px;
    margin: auto;
}

.li-left {
    width: 34%;
    float: left;
}

.li-right {
    float: right;
    width: 66%;
    position: relative;
    top: 30%;
}

#container .suggestion ul img {
    height: 180px
}

#container .suggestion ul li p {
    text-indent: 50px;
    line-height: 34px;
    font-size: 18px
}

#container .footer {
    height: 100px;
    text-align: center
}

#container .footer img {
    margin-top: 10px
}

#container .footer p {
    margin: 10px 0
}
</style>
