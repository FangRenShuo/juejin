<template>
    <div class="index">
        <!-- ================================================== 头部 ================================================== -->
        <div class="head">
            <!-- 一级标题 -->
            <div class="level-line">
                <level-one></level-one>
                <level-two></level-two>
            </div>
        </div>
    </div>
</template>

<script>
import LevelOne from "./LevelOne.vue";
import LevelTwo from "./LevelTwo.vue";

export default {
    components: {
        LevelOne,
        LevelTwo
    }
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
    margin: 0;
    padding: 0
}

/*设置默认字体*/
body {
    font-size: 14px;
    font-style: normal;
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
    text-decoration: none;
    background-color: transparent
}

a:hover,
a:active {
    outline-width: 0;
    text-decoration: none
}

/*重置表格*/
table {
    border-collapse: collapse;
    border-spacing: 0
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
    -webkit-touch-callout: none;
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
    height: 0
}

progress {
    vertical-align: baseline
}

mark {
    background-color: #ff0;
    color: #000
}

sub,
sup {
    position: relative;
    font-size: 75%;
    line-height: 0;
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
    outline: 0
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
    padding: 0
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
    padding: 0
}

[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
    height: auto
}

[type="search"] {
    -webkit-appearance: textfield;
    outline-offset: -2px
}

[type="search"]::-webkit-search-cancel-button,
[type="search"]::-webkit-search-decoration {
    -webkit-appearance: none
}

::-webkit-input-placeholder {
    color: inherit;
    opacity: .54
}

::-webkit-file-upload-button {
    -webkit-appearance: button;
    font: inherit
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
    /* 固定头部效果-end */

    /* max-width: 1440px; */
    background: white;
    height: 107px;
    box-shadow: 0 1px 2px 0 rgb(0 0 0 / 5%);
}
</style>