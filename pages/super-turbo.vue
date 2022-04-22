<template>
    <div class="div">
        <nuxt-content :document="article2"></nuxt-content>
    </div>
</template>

<script>
export default {
    async asyncData({$content}) {
        let article2 = await $content('artikel2').fetch()
        return {
            article2
        }
    },
}
</script>
<style scoped>
.artikel2Bild{
    width: 100px;
}
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