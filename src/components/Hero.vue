<template>
    <!-- hero section -->
        <div class="hero" id="home">
            <div class="hero-container">
                <h1 class="hero-heading">Tech Forum!</h1>
                <p class="hero-description">Discuss all the lastes technology news and trends</p>
                <button class="main-btn"><a href="#">GET AVADA NOW! ></a></button>
            </div>
        </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.hero {
    background-image: url("../assets/home_slider_bg.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 100vh;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.hero-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    max-width: 1200px;
    margin: 0 auto;
    height: 100vh;
    text-align: center;
    padding: 30px;
}
.hero-heading {
    font-size: 5rem;
    font-weight: bold;
    color: #fff;
    margin-bottom: 1rem;
}
.hero-description {
    font-size: 1rem;
    color: #aeaeae;
    margin-bottom: 2rem;
}
.main-btn {
    background-color: #27aabe;
    padding: 1rem;
    font-size: 1rem;
    font-weight: bold;
    color: #27aabe;
    cursor: pointer;
    border: none;
}
.main-btn a {
    color: #fff;
    text-decoration: none;
}
</style>