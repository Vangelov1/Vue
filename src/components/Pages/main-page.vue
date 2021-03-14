<template>
    <div class="main-container">

        <div class="navigation">
          <a href="Main.html"><img class="nav-logo" src="../images/logo.svg" alt=""></a>
            <div>
            <a href="Library.html" class="nav-button">Library</a>
            <a href="mood-profiles.html" class="nav-button">Mood Profiles</a>
            <a href="Nav-Button" class="nav-button">Plans</a>
            <a href="Nav-Button" class="nav-button">Places</a>
           </div>
            <div class="nav-user-buttons">
              <a href="" class="login">Log In</a>
              <a href="../Register.html" class="signup">Sign Up</a>
            </div>
        </div>

        <div class="main-body">

          <div class="top-section">
            <p class="top-title">Newly Published</p>
            <div class="slider">
              <div class="slide-a" id="slide-1">
                
              </div>
              <div class="slide" id="slide-2"></div>
              <div class="slide" id="slide-3"></div>
              <div class="slide" id="slide-3"></div>
            </div>
          </div>

          <div class="main-section">
          <div class="left">
            <div class="side-navigation">
              <ul class="side-nav-items">
                <li class="item">
                  <img src="../images/icons/stress.svg" alt="">
                  <p>Stress Release</p>
                </li>
                <li class="item">
                  <img src="../images/icons/stress.svg" alt="">
                  <p>Stress Release</p>
                </li>
                <li class="item">
                  <img src="../images/icons/stress.svg" alt="">
                  <p>Stress Release</p>
                </li>
                <li class="item">
                  <img src="../images/icons/stress.svg" alt="">
                  <p>Stress Release</p>
                </li>
                <li class="item">
                  <img src="../images/icons/stress.svg" alt="">
                  <p>Stress Release</p>
                </li>
                <li class="item">
                  <img src="../images/icons/stress.svg" alt="">
                  <p>Stress Release</p>
                </li>
              </ul>
            </div>
          </div>

          <div class="right">

          </div>
        </div>

        </div>




    </div>
</template>

<script>
export default {
  name: 'main-page',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
