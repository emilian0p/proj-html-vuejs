<template>
    <main>
        <Hero />
        <AvadaDivider />
        <LastNews />
        <Spacer />
    </main>
</template>

<script>
import Hero from "./Hero.vue";
import AvadaDivider from "./AvadaDivider.vue";
import LastNews from "./LastNews.vue";
import Spacer from "./Spacer.vue";

export default {
    components: {
        Hero,
        AvadaDivider,
        LastNews,
        Spacer
    },
};
</script>

<style lang="scss">
</style>