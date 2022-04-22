<template>
    <div class="div">
        <nuxt-content :document="article3"></nuxt-content>
    </div>

</template>

<script>
export default {
    async asyncData({$content}) {
        let article3 = await $content('artikel3').fetch()
        return {
            article3
        }
    },
}
</script>
<style scoped>
.div{
    background: rgba(0, 0, 0, 0.753);
    padding: 5px;
    color: whitesmoke;
    margin-left: 200px;
    margin-top: 10px;
    width: 70%;
    padding: 7px;
    }
</style>