<script setup>
    import { RouterLink } from 'vue-router';
    import '@fortawesome/fontawesome-free/css/all.css'


</script>

<template>
    <nav class="tab">
        <ul class="navigation">
          <select class="option">
            <option value="" disabled selected>Products</option>
            <option value="option1">Publisher</option>
            <option value="option2">Analytics</option>
          </select>
          <li class="nav-item">
            <a href="#" class="nav-link">Channels</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">Pricing</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">Contact</a>
          </li>
        </ul>
        <button class="button">Try for free</button>
      </nav>

      <div class="text">
        <h1>Manage all your<br>Social Accounts<br>with <span style="color: #44C079">one tool</span></h1>
        <p>Stay organized, save time, and easily manage <br>
            your social media with monitoring, and team <br>
            collaboration tools.</p>
        <button>Try Now</button>
      </div>

      <div class="img">
        <img src="../assets/Photo.png" alt="">
      </div>

      <div style="font-size: 44px">
        <i class="fa-brands fa-facebook" 
        style="color: #1977f3;
        position: absolute;
        left: 870px;
        top: -475px;"></i>

        <i class="fa-brands fa-instagram"
        style="color: #1977f3;
        position: absolute;
        left: 1065px;
        top: -450px;"></i>

        <i class="fa-brands fa-linkedin"
        style="color: #0A66C2;
        position: absolute;
        left: 1265px;
        top: -465px;"></i>

        <i class="fa-brands fa-youtube" 
        style="color: #FF0000;
        position: absolute;
        left: 960px;
        top: -350px;"></i>

        <i class="fa-brands fa-tiktok" 
        style="position: absolute;
        left: 1100px;
        top: -250px;"></i>

        <i class="fa-brands fa-twitter"
        style="color: #1D9BF0;
        position: absolute;
        left: 930px;
        top: -100px;"></i>
      </div>
      
      

      
</template>

<style scoped>
.tab {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100px;
  left: 0px;
  top: 0px;
}

.navigation {
  display: flex;
  flex-direction: row;
  list-style: none;
  margin-right: 20px;
  padding: 0 20px;
  height: 54px;
}

.nav-item {
  margin: 0 10px;
}

.nav-link {
  display: inline-block;
  padding: 10px 20px;
  text-decoration: none;
  font-size: 24px;
  font-weight: 400;
  color: black;
  background: #FFFFFF;
  font-family: 'Candara', sans-serif;
}

.option {
  background-color: transparent; 
  border: none;
  font-family: 'Candara', sans-serif;
  font-size: 24px;
  font-weight: 400;
  margin-left: 10px;
}

.button {
    position: absolute;
    right: 150px;
    background-color: transparent;
    border: 2px solid #44C079;
    border-radius: 15px;
    padding: 10px 20px;
    font-size: 24px;
    font-family: 'Candara';
    color: #44C079;
    font-weight: 400;
}
.text {
    position: absolute;
    width: 380px;
    height: 180px;
    left: 140px;
    top: 139px;
}
.text h1 {
    font-family: 'Source Sans Pro';
    font-style: normal;
    font-weight: 700;
    font-size: 48px;
    line-height: 60px;
    text-align: center;
    letter-spacing: 0.05em;
}

.text p {
    font-family: 'Candara';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 29px;
    color: #383838;
}

.text button {
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
    top: 60px;
    left: 100px;
    box-shadow: 20px 20px 50px #44C079, -20px -20px 50px #44C079;
}

.img img {
  width: 300px;
  height: 475px;
  left: 575px;
  top: -35px
  
}

.fa-brands fa-facebook{
  position: absolute;
  width: 100px;
  height: 100px;
  left: 1144px;
  top: 190px;
}

  
</style>