<script setup>
    import { RouterLink } from 'vue-router';


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
        <button class="but">Try Now</button>
      </div>

      <div>
        <div class="vector">
          <img src="../assets/images/Vector2.svg" alt="">
        </div>

        <div class="illustration2">
          <img src="../assets/images/Illustration2.svg" alt="">
        </div>

        <div class="img">
          <img src="../assets/images/Photo.png" alt="">
        </div>

        <div>
          <img src="../assets/images/Facebook.svg"  style="position: absolute; hight: 60px; width: 60px; left: 850px; top: -475px;" alt="">
          <img src="../assets/images/ig.svg"  style="position: absolute; hight: 60px; width: 60px; left: 985px; top: -440px;" alt="">
          <img src="../assets/images/in.svg"  style="position: absolute; hight: 60px; width: 60px; left: 1140px; top: -460px;" alt="">
          <img src="../assets/images/Youtube.svg"  style="position: absolute; hight: 60px; width: 60px; left: 890px; top: -340px;" alt="">
          <img src="../assets/images/tt.svg"  style="position: absolute; hight: 60px; width: 60px; left: 1000px; top: -240px;" alt="">
          <img src="../assets/images/t.svg"  style="position: absolute; hight: 60px; width: 60px; left: 885px; top: -110px;" alt="">
        </div>

        <div class="Card">
          <img src="../assets/images/Card.svg" alt="">
        </div>
      </div>


</template>

<style scoped>
  *{
     margin: 0;
     padding: 0;
    }
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
    width: 380px;
    height: 180px;
    margin-left: 8rem;
    margin-top: 3rem;
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

.but {
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
    margin-top: 60px;
    margin-left: 100px;
    box-shadow: 20px 20px 50px #44C079, -20px -20px 50px #44C079;
}

  .img img {
    width: 300px;
    height: 475px;
    margin-left: 550px;
    margin-top: -440px;
    margin-bottom: 0px;
    
  }
  .vector img {
    width: 650px;
    height: 400px;
    margin-left: 525px;
    margin-top: -230px;
    margin-bottom: 0px;
  }
  .illustration2 img{ 
    width: 180px;
    height: 120px;
    margin-left: 700px;
    margin-top: -150px;
    margin-bottom: 0px;
  }
  .Card img {
    width: 220px;
    height: 160px;
    margin-left: 990px;
    margin-top: -150px;
    margin-bottom: 0px;
  }

</style>