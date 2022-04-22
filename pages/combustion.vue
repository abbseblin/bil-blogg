<template>
    <div class="div">
        <nuxt-content :document="article"></nuxt-content>
    </div>

</template>

<script>
export default {
    async asyncData({$content}) {
        let article = await $content('artikel1').fetch()
        return {
            article
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