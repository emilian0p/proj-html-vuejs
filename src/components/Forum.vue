<template>
<div id="back">
    <div class="forum">
        <h3>PHASELLUS EGET METUS</h3>
        <p class="font">Forum Sections</p>
        <div class="space"></div> 
        <div class="container up">
            <div class="forum-items-container"><p>News & Community</p></div>
            <div class="forum-items-container"><p>Apple Forum</p></div>
            <div class="forum-items-container"><p>Microsoft Forum</p></div>
            <div class="forum-items-container"><p>Android Forum</p></div>
        </div>
        <div class="container down">
            <div class="forum-items-container"><p>General Discussion</p></div>
            <div class="forum-items-container"><p>Apps & Software</p></div>
            <div class="forum-items-container"><p>Gadgets and stuff</p></div>
            <div class="forum-items-container"><p>Tutorials & Guides</p></div>
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
}
div#back{
    background-color: #aeaeae;
}
div h3{
    font-size: .8rem;
    margin-bottom: 1rem;
    margin-top: 1rem;
}
div .font{
    font-size: 2rem;
    margin-bottom: 1rem;
    font-weight: bold;
}
div.forum{
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 2rem;
}
div.forum-items-container{
    margin-bottom: 2rem;
    background-color: #fff;
    margin-right: 2rem;
    border-top: 2px solid #74def4;
}
.space{
    background-color: #fc8c5e;
    height: 2px;
    width: 60px;
    justify-content: center;
    align-content: center;
    margin-bottom: 6rem;
}
div.container{
    justify-content: space-between;
    height: 10rem;
    width: 70%;
}  
div h4{
    font-size: .7rem;
}
p{
    font-size: .7rem;
    margin-bottom: 1rem;
    
}
</style>