<template>
<div id="back">
    <div class="forum">
        <h3>PHASELLUS EGET METUS</h3>
        <p class="font">Forum Sections</p>
        <div class="space"></div>
            <div class="container">
                <div class="forum-items-container"><p>News & Community</p></div>
                <div class="forum-items-container"><p>Apple Forum</p></div>
                <div class="forum-items-container"><p>Microsoft Forum</p></div>
                <div class="forum-items-container"><p>Android Forum</p></div>
            </div>
            <div class="container">
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
div#back{
    background-color: #aeaeae;
    height: 50vh;
    width: 100%;
    display: flex;
    align-items: center;
    text-align: center;
    justify-content: center;   
        h3 {
            font-size: .8rem;
            margin-bottom: 1rem;
            margin-top: 12rem;
        }
        .font {
            font-size: 2rem;
            margin-bottom: 1rem;
            font-weight: bold;
        }
        .space{
            background-color: #fc8c5e;
            height: 2px;
            width: 4rem;
            justify-content: center;
            align-content: center;
            margin-bottom: 20px;
            margin-left: 17rem;
        }
        .container{
            display: flex;
            flex-direction: row;
            height: 8rem;
            margin-bottom: 2rem;
            text-align: center;
                    .forum-items-container{ 
                        display: flex;
                        flex-direction: column;
                        justify-content: center;
                        text-align: center;                        align-items: center;
                        width: 100%;
                        height: 100%;
                        margin-right: 1rem;
                        background-color: #fff;
                        border-top: 3px solid #74def4;
                            p{
                                font-size: .7rem;
                                margin-right: 2rem;
                            }
                    }
            }
        }

</style>