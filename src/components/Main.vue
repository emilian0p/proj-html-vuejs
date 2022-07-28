<template>
    <main>
        <Hero />
        <AvadaDivider />
        <LastNews />
        <Spacer />
        <Forum />
    </main>
</template>

<script>
import Hero from "./Hero.vue";
import AvadaDivider from "./AvadaDivider.vue";
import LastNews from "./LastNews.vue";
import Spacer from "./Spacer.vue";
import Forum from "./Forum.vue";

export default {
    components: {
        Hero,
        AvadaDivider,
        LastNews,
        Spacer,
        Forum,
    },
};
</script>

<style lang="scss">
</style>