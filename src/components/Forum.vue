<template>
    <div>
        <h3>PHASELLUS EGET METUS</h3>
        <p>Forum Sections</p>
        <div class="space"></div> 
        <div class="container">
            <div class="up">
                <div class="item">
                    <img src="" alt="">
                    <p>News & Community</p>
                </div>
                <div class="item">
                    <img src="" alt="">
                    <p>Apple Forum</p>
                </div>
                <div class="item">
                    <img src="" alt="">
                    <p>Microsoft Forum</p>
                </div>
                <div class="item">
                    <img src="" alt="">
                    <p>Android Forum</p>
                </div>
            </div>
            <div class="down">
                <div class="item">
                    <img src="" alt="">
                    <p>General Discussion</p>
                </div>
                <div class="item">
                    <img src="" alt="">
                    <p>App & Software</p>
                </div>
                <div class="item">
                    <img src="" alt="">
                    <p>Gadget & Stuff</p>
                </div>
                <div class="item">
                    <img src="" alt="">
                    <p>Tutorials & Guides</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
div{
    display: flex;
    flex-direction: column;
    align-items: center;    

}
div.container{
    display: flex;
    flex-direction: row;
}
div.up{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    width: 100%;
}
div h3{
    font-size: .8rem;
    margin-bottom: 1rem;
    margin-top: 1rem;
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
    margin-bottom: 6rem;
}
</style>