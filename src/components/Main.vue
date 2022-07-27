<template>
    <main>
        <Hero />
        <AvadaDivider />
        <LastNews />
    </main>
</template>

<script>
import Hero from "./Hero.vue";
import AvadaDivider from "./AvadaDivider.vue";
import LastNews from "./LastNews.vue";
export default {
    components: {
        Hero,
        AvadaDivider,
        LastNews
    },
};
</script>

<style lang="scss">

</style>