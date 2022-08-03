<template>
    <div id="article">
        <p>这是文章内容： {{ value }}</p>
    </div>
</template>

<script>
export default {
    props: {
        value: { required: true, type: String }
    }
}
</script>

<style>
#article {
    width: 700px;
    height: 133px;
    background-color: #fff;
    border-bottom: 1px solid #000;
}
</style>