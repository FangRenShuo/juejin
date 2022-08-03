<template>
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
</template>
<script></script>
<style>
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