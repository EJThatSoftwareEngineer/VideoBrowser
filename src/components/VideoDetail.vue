<template>
    <div v-if="video">
        {{ video.snippet.title }} test
    </div>
</template>
<script>
export default {
    name:'VideoDetail',
    props:['video']
};
</script>
<style scoped>

</style>
