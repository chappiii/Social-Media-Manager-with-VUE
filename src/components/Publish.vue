<script setup>
    import { RouterLink } from 'vue-router';
</script>

<template>
    <div class="publish">
        <h1>publish</h1>
        <h2>Post and Schedule all big<br>social Medias</h2>
        <p>Our all-in-one social media <br> management platform unlocks the full <br> potential of social to transform not just <br> your marketing strategy—but every <br> area of your organization.</p>
        <div class="icon">
            <div>
                <a href=""><img src="../assets/images/Facebook.svg" alt=""><p>Facebook</p></a>
                <a href=""><img src="../assets/images/ig.svg" alt=""><p>Instagram</p></a>
                <a href=""><img src="../assets/images/in.svg" alt=""><p>Linkedin</p></a>
            </div>
            <div >
                <a href=""><img src="../assets/images/tt.svg" alt=""><p>TikTok</p></a>
                <a href=""><img src="../assets/images/Youtube.svg" alt=""><p>Youtube</p></a>
                <a href=""><img src="../assets/images/t.svg" alt=""><p>Twitter</p></a>
            </div>
        </div>


        <div class="button">
            <button>Start Now</button>
        </div>
    </div>
    
    <div class="ill">
        <img src="../assets/images/Illustration3.svg" alt="">
    </div>

    <div class="image">
        <img src="../assets/images/Image.svg" alt="">
    </div>

    <div class="roph1">
        <img src="../assets/images/roph1.svg" alt="">
    </div>
      
    <div class="orang_tt">
        <img src="../assets/images/orang_tt.svg" alt="">
    </div>

    <div class="Facebook_icon">
        <img src="../assets/images/Facebook_icon.svg" alt="">
    </div>

    <div class="vec">
        <img src="../assets/images/vec.svg" alt="">
    </div>

    <div class="ill02">
        <img src="../assets/images/Illustration3.svg" alt="">
    </div>
    
</template>

<style scoped>
    *{
        margin: 0;
        padding: 0;
    }
    .publish {
        margin-left: 140px;
        margin-top: 120px;
    }
    .publish h1 { 
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 30px;
        line-height: 54px;
        color: #44C079;
        padding-bottom: 10px;
    }
    .publish h2 {
        font-family: 'Open Sans';
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        line-height: 33px;
        padding-bottom: 10px;
    }
    .publish p {
        font-family: 'Open Sans';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 33px;
    }
    .icon {
        display: grid;
        grid-template-columns: repeat(8, 1fr);
    }
    .icon div {
        display: flex;
        flex-direction: column;
    }
    .icon img{
        height: 20px;
        width: 20px;
        display: inline-block;
        margin: 0;
    }
    .icon p{
        font-size: 15px;
        margin: 0;
        display: inline-block;
        color: black;
    }
    .button button {
        background-color: #44C079;
        border: 2px solid #44C079;
        border-radius: 15px;
        padding: 5px 35px;
        font-size: 24px;
        font-family: 'Candara';
        color: white;
        font-weight: 400;
        font-weight: 700;
        line-height: 35px;
        text-align: center;
        letter-spacing: 0.05em;
        margin-top: 50px;
        margin-left: 10px;
        box-shadow: 20px 20px 50px #44C079, -20px -20px 50px #44C079;
    }

    .ill img{
        width: 117px;
        height: 101px;
        margin-left: 700px;
        top: -610px;
    }
    .image img {
        width: 400px;
        height: 295px;
        margin-left: 750px;
        top: -640px;
    }
    .roph1 img {
        width: 200px;
        height: 290px;
        margin-left: 615px;
        top: -765px;
    }
    .orang_tt img{
        width: 118.13px;
        height: 84.11px;
        margin-left: 695px;
        top: -1160px;
    }
    .Facebook_icon img{
        width: 80px;
        height: 80px;
        margin-left: 835px;
        top: -1060px;
    }
    .vec img {
        width: 134.21px;
        height: 57.52px;
        margin-left: 770px;
        top: -1090px;
    }
    .ill02 img{
        width: 130px;
        height: 115px;
        margin-left: 1180px;
        top: -1090px;    
    }
</style>