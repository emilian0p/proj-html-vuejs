<template>
    <div class="last-news-container" id="home">
                <h3 class="last-news-heading">PHASELLUS EGET METUS</h3>
                <p class="last-news-description">All the lastest news</p>
                <div class="space">.</div>
                <div class="articles-container">
                        <div class="article">
                            <img src="../assets/post_feat_img_25-320x202.jpg" alt="">
                            <h5>Morbi vitae</h5>
                            <p>Data</p>
                            <p>
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </p>
                        </div>
                        <div class="article">
                            <img src="../assets/post_feat_img_25-320x202.jpg" alt="">
                            <h5>Morbi vitae</h5>
                            <p>Data</p>
                            <p>
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </p>
                        </div>
                        <div class="article">
                            <img src="../assets/post_feat_img_25-320x202.jpg" alt="">
                            <h5>Morbi vitae</h5>
                            <p>Data</p>
                            <p>
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </p>
                        </div>
                </div>
                <div class="big-article">
                    <h3>FEATURED ARTICLE</h3>
                    <p class="semi-title">Cras malesuada et orci eget pharetra</p>
                    <p class="description">
                        Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                    </p>
                    <button class="btn"><a href="#">READ MORE ></a></button>
                </div>
                <div class="articles-container">
                        <div class="article">
                            <img src="../assets/post_feat_img_25-320x202.jpg" alt="">
                            <h5>Morbi vitae</h5>
                            <p>Data</p>
                            <p>
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </p>
                        </div>
                        <div class="article">
                            <img src="../assets/post_feat_img_25-320x202.jpg" alt="">
                            <h5>Morbi vitae</h5>
                            <p>Data</p>
                            <p>
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </p>
                        </div>
                        <div class="article">
                            <img src="../assets/post_feat_img_25-320x202.jpg" alt="">
                            <h5>Morbi vitae</h5>
                            <p>Data</p>
                            <p>
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </p>
                        </div>
                </div>
                <div class="aside-container">
                        <div class="second-big-article">
                            <h3>FEATURED ARTICLE</h3>
                            <p class="semi-title">Cras malesuada et orci eget pharetra</p>
                            <p class="description">
                                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                            </p>
                            <button class="btn"><a href="#">READ MORE ></a></button>
                        </div> 
                        <aside>
                            <h2>Tutorials & Guides</h2>
                            <div class="space"></div>
                            <div class="aside-article">
                                <img src="../assets/post_feat_img_23-147x118.jpg" alt="">
                            </div>
                            <div class="aside-article">
                                <img src="../assets/post_feat_img_23-147x118.jpg" alt="">
                            </div>
                            <div class="aside-article">
                                <img src="../assets/post_feat_img_23-147x118.jpg" alt="">
                            </div>
                        </aside>   
                        
                </div>
        </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
div#home{
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 100vh;
    margin-left: 5rem;
    margin-right: 5rem;
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
    margin-bottom: 20px;
}
div.articles-container{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    width: 100%;
    margin-top: 2rem;

}
div.article{
    margin: 0 2rem 0 2rem;
    display: inline-block;
    height: 11rem;
}
div.article p{
    font-size: .7rem;
    margin-bottom: 1rem;
    color: #aeaeae;
}
div img{
    width: 100%;
}
div.big-article{
    width: 90%;
    height: 40vh;
    background-image: url("../assets/featured_article_1_bg.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    padding: 4rem;
    padding-top: 8rem;
    color: #fff;
}
div.big-article h3{
    font-size: .6rem;
}
div p.semi-title{
    font-size: 1.5rem;
}
div p.description{
    font-size: .5rem;
}
.btn{
    background-color: black;
    color: #fff;
    border: none;
    padding: .5rem;
    margin-top: 1rem;
}
.btn a{
    color: #fff;
    text-decoration: none;
}
div.second-big-article{
    background-image: url("../assets/featured_article_1_bg.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    padding: 4rem;
    padding-top: 8rem;
    color: #fff;
}
div.aside-container{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    width: 100%;
    margin-right: 1rem;
}
div.second-big-article{
    margin-right: 2rem;
}
div.second-big-article h3{
    font-size: .6rem;
}
aside h2{
    font-size: 1.3rem;
}
</style>