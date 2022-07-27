<template>
    <div class="last-news-container" id="home">
                <h3 class="last-news-heading">PHASELLUS EGET METUS</h3>
                <p class="last-news-description">All the lastest news</p>
                <div class="space">.</div>
                <div class="articles">
                    <div></div>
                    <div></div>
                    <div></div>
                </div>
        </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
#home{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100px;
}
div h3{
    font-size: .8rem;
    margin-bottom: 1rem;
    margin-top: 3rem;
}
div p{
    font-size: 2rem;
    margin-bottom: 1rem;
    font-weight: bold;

}
.space{
    background-color: #fc8c5e;
    height: 2px;
    width: 60px;
    justify-content: center;
    align-content: center;
}
</style>