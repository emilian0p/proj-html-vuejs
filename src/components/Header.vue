<template>
    <header>
        <nav class="navbar">            
            <div class="navbar-container">
                <img src="../assets/logo.png"id="navbar-logo" alt="">
                <ul class="navbar-menu">
                    <li class="navbar-item" ><a class="navbar-links" href="#" id="home-page">Home</a></li>
                    <li class="navbar-item" ><a class="navbar-links" href="#" id="apple-page">Apple</a></li>
                    <li class="navbar-item" ><a class="navbar-links" href="#" id="microsoft-page">Microsoft</a></li>
                    <li class="navbar-item" ><a class="navbar-links" href="#" id="android-page">Android</a></li>
                    <li class="navbar-item" ><a class="navbar-links" href="#" id="forums-page">Forums</a></li>
                    <li class="navbar-item" ><a class="navbar-links" href="#" id="contact-page">Contact us</a></li>
                    <li class="navbar-btn" ><a class="button" href="#" id="join-us">JOIN US</a></li>
                    <li class="navbar-item"><a class="navbar-links" href="#"><!-- lente --></a></li>
                </ul>
            </div>
        </nav>
    </header>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.navbar {
    background-color: #27aabe;
    height: 80px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    position: sticky;
    top: 0;
    z-index: 10;
}
.navbar-container {
    display: flex;
    justify-content: space-between;
    height: 80px;
    z-index: 1;
    width: 100%;
    max-width: 1300px;
    margin: 0 auto;
    padding: 0 50px;
}
#navbar-logo {
    background-size: 70%;
    height: 50px;
    width: 200px;
    display: flex;
    align-items: center;
    margin-top: 10px;
    cursor: pointer;
}
.navbar-menu {
    display: flex;
    align-items: center;
    margin-top: 10px;
    list-style: none;
}
.navbar-item {
    height: 80px;
    margin-right: 1rem;
    margin-top: 2rem;
    
}
.navbar-links{
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 125px;
    text-decoration: none;
    width: 100%;
}
.navbar-btn{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0 1rem;
    width: 100%;
}
.button{
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    padding: 10px 20px;
    height: 100%;
    width: 100%;
    border: none;
    outline: none;
    background: #1a1b1b;
    color: #fff;
}
.navbar-links:hover{
    color: #fc8c5e;
}



</style>