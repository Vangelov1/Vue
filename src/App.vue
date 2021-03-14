<template>
<div class="main-container">

<div class="content">
  <div class="top">
      <img src="./assets/logo.svg" alt="">
      <div class="nav-user-buttons">
        <a href="" class="login">Log In</a>
        <a href="../Register.html" class="signup">Sign Up</a>
      </div>
   </div>  
    <div class="middle">
        <img src="./assets/m.svg" alt="">
        <p class="title">Breathe life into your surroundings !</p>
        <p class="subtitle">A powerfull tool to empower your mood.</p>
        <a href="Pages/Main.html" class="get-started">Get Started</a>
    </div>
    <div class="bottom">
        <p class="ending">Or download the mobile version.</p>
        <img src="./assets/gplay.svg" alt="" class="gplay">
        <img src="./assets/astore.svg" alt="">
    </div>
    </div>
</div>
</template>













<script>


export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


body {
margin: 0px;
padding: 0px;
background-image: url(./assets/bgg.png);

background-repeat: no-repeat;
background-position: right;
background-color: #F7FAF9;
}

.main-container {
max-height: 100vh;
width: 100%;
height: 100vh;
overflow: none;
}

.get-started {
    background: #90CAA1; /* Green */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    font-family: 'Inter', sans-serif;
    border-radius: 6px;
}



.bottom {
margin-bottom: 15px;
}

.content {
margin-left: 15px;
display: flex;
flex-flow: column;
justify-content: space-between;
height: 100%;
}

.top {
    margin-top: 15px;
    padding-right: 15px;
    display: flex;
    flex-flow: row;
    justify-content: space-between;
}

.logo2 {
    padding-bottom: 15px;
}

.gplay {
    padding-right: 10px;
}
.astore {
    padding-left: 15px;
}


.title {
font-family: 'Inter', sans-serif;
font-size: 40px;
width: 33%;
font-weight: 700;
margin: 0px;
padding-top: 15px;
color: #272727;
}


.subtitle {
font-family: 'Inter', sans-serif;
color: #5F5D5D;
font-size: 18px;
}

.ending {
font-family: 'Inter', sans-serif;
color: #5F5D5D;
font-size: 14px;
width: 90%;
}

.signup {
    padding: 11px;
    
    background: #ffff;
    border-radius: 4px;
    font-family: 'Inter', sans-serif;
    text-decoration: none;
    color: #90CAA1;
    padding-right: 20px;
    padding-left: 20px;
}

.login {
    padding: 9px;
    margin-right: 20px;
    padding-right: 20px;
    padding-left: 20px;
    border: 1px solid #fff;
    box-sizing: border-box;
    border-radius: 4px;
    font-family: 'Inter', sans-serif;
    text-decoration: none;
    color: #fff
    ;
}

input[type=text] {
    width: 30%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
  }

  .middle-logo {
      padding-bottom: 15px;
  }

  .middle-logo-row {
    display: flex;
    flex-flow: row;
    font-family: 'Inter', sans-serif;
    font-size: 40px;
    align-items: baseline;
  }




</style>
