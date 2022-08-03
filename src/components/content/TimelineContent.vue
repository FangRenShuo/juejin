<template>
    <div id="timeline_content">
        <div id="left">
            <header class="list-header">
            </header>
            <div>
                <!-- 渲染文章组件 -->
                <li v-for="item in articles" :key="item.id">
                    <article-vue :value="item.value"></article-vue>
                </li>
            </div>
        </div>
        <div id="right">
            <signin-tip></signin-tip>
            <banner-block></banner-block>
            <banner-block></banner-block>
            <app-download></app-download>
            <user-block></user-block>
            <link-block></link-block>
        </div>
    </div>
</template>

<script>
import ArticleVue from './article/ArticleVue.vue'
import uniqueId from "lodash.uniqueid"; // 一个可以生成唯一id的插件
import SigninTip from './SigninTip.vue';
import BannerBlock from './BannerBlockVue.vue';
import AppDownload from './AppDownload.vue';
import UserBlock from './UserBlock.vue';
import LinkBlock from './LinkBlock.vue';

export default {
    components: {
        ArticleVue,
        SigninTip,
        BannerBlock,
        AppDownload,
        UserBlock,
        LinkBlock,
    },
    data() {
        return {
            // 文章数组
            articles: [
                { value: 1, id: uniqueId('article-') },
                { value: 2, id: uniqueId('article-') },
                { value: 3, id: uniqueId('article-') },
                { value: 4, id: uniqueId('article-') },
                { value: 5, id: uniqueId('article-') },
                { value: 6, id: uniqueId('article-') },
                { value: 7, id: uniqueId('article-') },
                { value: 8, id: uniqueId('article-') },
                { value: 9, id: uniqueId('article-') },
                { value: 10, id: uniqueId('article-') },
            ],
        }
    },
}
</script>

<style>
#timeline_content {
    position: relative;
    margin: 0 auto;
    margin-top: 10px;
    width: 960px;
}

#left {
    position: absolute;
}

#right {
    position: relative;
    left: 720px;
}

.list-header {
    width: 700px;
    height: 46px;
    background-color: #FFF;
    border-bottom: 1px solid #000;
}

li {
    list-style: none;
}
</style>