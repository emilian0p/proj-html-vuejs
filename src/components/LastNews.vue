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
                            <h3>REVIEWED PRODUCT</h3>
                            <p class="second-semi-title">Mauris viverra atisan ipsum eget felis primis efficitur varius</p>
                            <p class="second-description">
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
div#home {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 100vh;
    width: 70%;
    margin-left: 5rem;
    margin-right: 5rem;
    margin-bottom: 45rem;
    margin-top: 5rem;

        h3 {
            font-size: .8rem;
            margin-bottom: 1rem;
            margin-top: 1rem;
            
        }
        .last-news-description {
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
        }
        .articles-container {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: center;
            width: 100%;
            margin-bottom: 2rem;
        }
        .article {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            width: 30%;
            height: 15rem;
            margin-bottom: 2rem;
            margin-top: 2rem;
                p{
                    font-size: .7rem;
                    margin-bottom: 1rem;
                    color: #aeaeae;
                }
        }
        .article img {
            width: 100%;
            height: 100%;
        }
        .article h5 {
            font-size: .8rem;
            margin-bottom: 1rem;
            margin-top: 1rem;
        }
        .big-article{
            width: 100%;
            height: 40rem;
            background-image: url("../assets/featured_article_1_bg.jpg");
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            padding: 6rem;
            padding-top: 10rem;
            margin-bottom: 2rem;
            color: #fff;
            text-align: start;
        }
        .btn{
            background-color: black;
            color: #fff;
            border: none;
            padding: .5rem;
            margin-top: 1rem;
                a{
                    color: #fff;
                    text-decoration: none;
                }
        }
        p.semi-title{
            font-size: 1.5rem;
            font-weight: bold;
        }
        p.description{
            font-size: .5rem;
        }
        .aside-container{
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            width: 100%;
            margin-bottom: 2rem;
                .second-big-article{
                    background-image: url("../assets/featured_article_1_bg.jpg");
                    background-size: cover;
                    text-align: start;
                    padding: 4rem;
                    padding-top: 8rem;
                    margin-right: 2rem;
                    color: #fff;
                    height: 100%;
                        .second-semi-title{
                            font-size: 1.5rem;
                            margin-bottom: .5rem;
                            font-weight: bold;
                        }
                        .second-description{
                            font-size: .5rem;
                        }
                }
        }    
}
</style>