<template>
    <div>
        <header-vue></header-vue>
        <timeline-content></timeline-content>
    </div>
</template>
<script>
import HeaderVue from "./components/header/HeaderVue.vue";
import TimelineContent from "./components/content/TimelineContent.vue"

export default {
    components: {
        HeaderVue,
        TimelineContent,
    }
}
</script>
