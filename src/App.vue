<template>
      <div class="index">
        <!-- ================================================== 头部 ================================================== -->
        <div class="head">
            <!-- 一级标题 -->
            <div class="level-line">
                <div class="level-1">
                    <img src="https://lf3-cdn-tos.bytescm.com/obj/static/xitu_juejin_web/e08da34488b114bd4c665ba2fa520a31.svg" alt="稀土掘金" />
                    <ul class="nav">
                        <li><a href="#" style="color: #1e80ff;">首页</a></li>
                        <li><a href="#">沸点</a></li>
                        <li><a href="#">课程</a></li>
                        <li><a href="#">直播</a></li>
                        <li><a href="#">资讯</a></li>
                        <li><a href="#">活动</a></li>
                        <li class="link-item">
                            <a href="#">开放社区</a>
                            <img src="https://lf3-cdn-tos.bytescm.com/obj/static/xitu_juejin_web/e700f44c0c9ddafb97f655043d1c135a.svg" alt="稀土掘金" />
                        </li>   
                        <li class="link-new">
                            <a href="#">商城</a>
                            <span class="new-font">NEW</span>
                        </li>
                        <li><a href="#">APP</a></li>
                        <li><a href="#">插件</a></li>
                    </ul>
           
       
                    <!-- 搜索框 -->
                    <div class="search">
                        <div class="search-item">
                            <input type="search" maxlength="32" placeholder="探索稀土掘金" />
                            <div class="img-contanter">
                                <img src="https://lf3-cdn-tos.bytescm.com/obj/static/xitu_juejin_web/1e8ab9a22f0ddc36349f60b38900d0bd.svg" alt="搜索" />
                            </div>
                        </div>
                    </div>
                    <!-- 按钮 -->
                    <div class="btn">
                        <button>创作者中心</button>
                        <div>
                            <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg" data-v-75290ab2=""><path d="M2.45025 4.82383C2.17422 4.49908 2.40501 4 2.83122 4H9.16878C9.59499 4 9.82578 4.49908 9.54975 4.82382L6.38097 8.5518C6.1813 8.7867 5.8187 8.7867 5.61903 8.5518L2.45025 4.82383Z" fill="white" data-v-75290ab2=""></path></svg>
                        </div>
                    </div>
                    <!-- 提示通知 -->
                    <div class="notice">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" data-v-75290ab2=""><path d="M6.01132 10.2856C6.28115 6.54234 8.68619 4.28564 11.9999 4.28564C15.3136 4.28564 17.7186 6.54234 17.9885 10.2856C18.1219 12.1363 18.4093 13.708 19.9473 15.8848C20.1889 16.2267 19.953 16.7142 19.5343 16.7142H4.46546C4.04679 16.7142 3.81092 16.2267 4.05252 15.8848C5.59053 13.708 5.87793 12.1363 6.01132 10.2856Z" stroke-width="1.5" stroke-linecap="round" data-v-75290ab2=""></path><path d="M11.9573 3.21436V4.28578" stroke-width="3" stroke-linecap="round" data-v-75290ab2=""></path><path d="M9.57495 18.8569C9.92795 19.8557 10.8804 20.5712 12.0001 20.5712C13.1197 20.5712 14.0722 19.8557 14.4252 18.8569H9.57495Z" stroke-linecap="round" stroke-linejoin="round" data-v-75290ab2=""></path></svg>
                    </div>
                    <!-- 头像 -->
                    <div class="head-img">
                        <img src="https://p26-passport.byteacctimg.com/img/user-avatar/444d5ae9aab93a927483e78a2801b14a~300x300.image" alt="福隆苑居士" />
                    </div>
                </div>
            <div class="level-2">
                <div class="left">
                    <a href="#" style="color: #1e80ff; padding-left: 0;">综合</a>
                    <a href="#">关注</a>
                    <a href="#">后端</a>
                    <a href="#">前端</a>
                    <a href="#">Android</a>
                    <a href="#">iOS</a>
                    <a href="#">人工智能</a>
                    <a href="#">开发工具</a>
                    <a href="#">代码人生</a>
                    <a href="#">阅读</a>
                </div>
                <div class="right">
                    <a href="#" class="label">标签管理</a>
                </div>
            </div>
            </div>
       </div>
     </div>
</template>

<script>
 
export default {

}
</script>

<style>
body,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
p,
blockquote,
dl,
dt,
dd,
ul,
ol,
li,
button,
input,
textarea,
th,
td {
    margin : 0;
    padding: 0
}

/*设置默认字体*/
body {
    font-size  : 14px;
    font-style : normal;
    font-family: -apple-system, BlinkMacSystemFont, segoe ui, Roboto, helvetica neue, Arial, noto sans, sans-serif, apple color emoji, segoe ui emoji, segoe ui symbol, noto color emoji;
}

/*字体太小用户体检不好，让small恢复12px*/
small {
    font-size: 12px
}

h1 {
    font-size: 18px
}

h2 {
    font-size: 16px
}

h3 {
    font-size: 14px
}

h4,
h5,
h6 {
    font-size: 100%
}

ul,
ol {
    list-style: none
}

a {
    text-decoration : none;
    background-color: transparent
}

a:hover,
a:active {
    outline-width  : 0;
    text-decoration: none
}

/*重置表格*/
table {
    border-collapse: collapse;
    border-spacing : 0
}

/*重置hr*/
hr {
    border: 0;
    height: 1px
}

/*图形图片*/
img {
    border-style: none
}

img:not([src]) {
    display: none
}

svg:not(:root) {
    overflow: hidden
}

/*下面的操作是针对于html5页面布局准备的，不支持ie6~8以及其他低版本的浏览器*/
html {
    /*禁用系统默认菜单*/
    -webkit-touch-callout   : none;
    /*关闭iphone & Android的浏览器纵向和横向模式中自动调整字体大小的功能*/
    -webkit-text-size-adjust: 100%
}

input,
textarea,
button,
a {
    /*表单或者a标签在手机点击时会出现边框或彩色的背景区域，意思是去除点击背景框*/
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0)
}

/*重置html5元素的默认样式*/
article,
aside,
details,
figcaption,
figure,
footer,
header,
main,
menu,
nav,
section,
summary {
    display: block
}

audio,
canvas,
progress,
video {
    display: inline-block
}

audio:not([controls]),
video:not([controls]) {
    display: none;
    height : 0
}

progress {
    vertical-align: baseline
}

mark {
    background-color: #ff0;
    color           : #000
}

sub,
sup {
    position      : relative;
    font-size     : 75%;
    line-height   : 0;
    vertical-align: baseline
}

sub {
    bottom: -0.25em
}

sup {
    top: -0.5em
}

button,
input,
select,
textarea {
    font-size: 100%;
    outline  : 0
}

button,
input {
    overflow: visible
}

button,
select {
    text-transform: none
}

textarea {
    overflow: auto
}

button,
html [type="button"],
[type="reset"],
[type="submit"] {
    -webkit-appearance: button
}

button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
    border-style: none;
    padding     : 0
}

button:-moz-focusring,
[type="button"]:-moz-focusring,
[type="reset"]:-moz-focusring,
[type="submit"]:-moz-focusring {
    outline: 1px dotted ButtonText
}

[type="checkbox"],
[type="radio"] {
    box-sizing: border-box;
    padding   : 0
}

[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
    height: auto
}

[type="search"] {
    -webkit-appearance: textfield;
    outline-offset    : -2px
}

[type="search"]::-webkit-search-cancel-button,
[type="search"]::-webkit-search-decoration {
    -webkit-appearance: none
}

::-webkit-input-placeholder {
    color  : inherit;
    opacity: .54
}

::-webkit-file-upload-button {
    -webkit-appearance: button;
    font              : inherit
}
 /* 以上整体样式 */
body {
    background: #f4f5f5;
}

.index {
    display: flex;
}

/*------------------------------------------- 头部 -------------------------------------------*/

.head {
    /* 固定头部效果-start 说明：fixed后会脱离页面元素，页面元素会跳到顶部去，所以主体margin-top要设置为head的高度+想要margin-top的距离。 */
    top: 0;
    left: 0;
    right: 0;
    width: 100%;
    position: fixed;
    /* 固定头部效果-end */

    /* max-width: 1440px; */
    background: white;
    height: 107px;
    box-shadow: 0 1px 2px 0 rgb(0 0 0 / 5%);
}

/*----------------------- 一级标题部分 -----------------------*/
.level-line {
    height: 60px;
    line-height: 60px;
    border-bottom: 1px solid #f1f1f1;
}

.level-1 {
    display: flex;
    align-items: center;

    height: 100%;

    margin: 0 auto;
    max-width: 1440px;
}

.level-1>img {
    width: 107px;
    height: 22px;
    margin-left: 24px;
}

.nav {
    display: flex;
    flex-shrink: 0;
}

.nav>li {
    margin-left: 23px;
    color: #515767;
    font-size: 14px;
}

.nav>li>a {
    color: #515767;
}

.nav>li>a:hover {
    color: #1e80ff;
}

.link-item {
    display: flex;
    align-items: center;
    width: 69px;
}

.link-item>img {
    padding-left: 5px;
}

.link-new {
    display: flex;
}

.link-new>span {
    position: absolute;
    height: 20px;
    line-height: 20px;
    font-size: 16px;
    transform: scale(.5);
    top: 4px;
    padding: 0 6px;
    margin: 0 0 0 10px;
    background: #f64242;
    border: 1px solid #fff;
    border-radius: 50px;
    color: #fff;
    white-space: nowrap;
}

.search {
    padding-left: 115px;
}

.search-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 360px;
    border: 1px solid #c2c8d1;
    border-radius: 4px;
}

.search-item:hover {
    border: 1px solid #999;
    border-radius: 4px;
}

.search-item>input {
    border: none;
    padding: .6rem 0 .6rem 1rem;
    box-shadow: none;
    outline: none;
    width: 316px;
    font-size: 14px;
    color: #8a919f;
    background-color: transparent;
    transition: width .3s;
}

.search-item .img-contanter {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 30px;
    width: 44px;
    background: #f2f3f5;
    border-radius: 2px;
}

.img-contanter>img {
    cursor: pointer;
}

.btn {
    display: flex;
    align-items: center;
    height: 36px;
    margin-left: 25px;
}

.btn>button {
    border: none;
    border-radius: 3px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    width: 94px;
    height: 100%;
    color: #fff;
    background-color: #1e80ff;
    cursor: pointer;
}

.btn>button:hover {
    background-color: #1171ee;
}

.btn>div {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 20px;
    height: 100%;
    background-color: #1e80ff;
    border-left: 1px solid hsla(0,0%,100%,.1);
    border-radius: 3px;
    border-top-left-radius: 0;
    border-bottom-left-radius: 0;
    cursor: pointer;
}

.btn>div:hover {
    background-color: #1171ee;
}

.notice {
    margin-left: 25px;
    display: flex;
    align-items: center;
}

.notice>svg {
    fill: #8a919f;
    stroke: #8a919f;
    cursor: pointer;
}

.notice>svg:hover {
    fill: #515767;
    stroke: #515767;
}

.head-img {
    display: block;
    margin-left: 27px;
}

.head-img>img {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    background-color: #eee;
    cursor: pointer;
}
.level-2 {
    display: flex;
    justify-content: space-between;
    align-items: center;
    min-width: min-content;
    max-width: 960px;
    margin: 0 auto;

    font-size: 13.92px;
    line-height: 46px;
}

.level-2 .right {
    display: flex;
    justify-content: end;
}

.level-2 .right .label {
    padding-right: 0;
}

.level-2 a {
    color: #71777c;
    padding: 0 12px;
}

.level-2 a:hover {
    color: #1e80ff;
}
</style>
