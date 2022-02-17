<template>
    <div>
        <div class="main">
        <div class="child">
        <div style="text-align: left;"><b-navbar-brand href="#" style="margin-left: 20px;"><b-icon-linkedin size="lg"></b-icon-linkedin></b-navbar-brand></div>
    <p style="text-align: left;">Navigation</p>
    <b-row>
    <b-col><a href="#" style="text-decoration: none;">About</a></b-col>
    <b-col><a href="#" style="text-decoration: none;">Talent Solutions</a></b-col>
    <b-col><a href="#" style="text-decoration: none;">Advertising</a></b-col>
    <b-col><a href="#" style="text-decoration: none;">Community</a></b-col>
  </b-row>
    <b-row>
    <b-col><a href="#" style="text-decoration: none;">Careers</a></b-col>
    <b-col><a href="#" style="text-decoration: none;">Marketing Solutions</a></b-col>
    <b-col><a href="#" style="text-decoration: none;">Privacy and Terms </a></b-col>
    <b-col><a href="#" style="text-decoration: none;"></a></b-col>
    </b-row>
  <b-row>
    <b-col><a href="#" style="text-decoration: none;">Advertising</a></b-col>
    <b-col><a href="#" style="text-decoration: none;">Sales Solutions</a></b-col>
    <b-col><a href="#" style="text-decoration: none;">Mobile App</a></b-col>
    <b-col><a href="#" style="text-decoration: none;"></a></b-col>
  </b-row>
  <b-row>
    <b-col><a href="#" style="text-decoration: none;">Small Business</a></b-col>
    <b-col><a href="#" style="text-decoration: none;">Safety Center</a></b-col>
    <b-col><a href="#" style="text-decoration: none;"></a></b-col>
    <b-col><a href="#" style="text-decoration: none;"></a></b-col>
  </b-row>
    </div>
    <div class="twochilds">
        <p>Fast Access</p>
        <b-button variant="primary" style="margin-right: 10px">Questions</b-button>
        <br>
        <br>
        <b-button variant="outline-primary">Settings</b-button>
    </div>
    <div class="twochilds">
        <p>Language</p>
        <b-navbar-nav class="ml-auto">
        <b-nav-item-dropdown text="ENGLISH" right>
          <b-dropdown-item href="#">ENGLISH</b-dropdown-item>
          <b-dropdown-item href="#">FRENCH</b-dropdown-item>
          <b-dropdown-item href="#">GERMAN</b-dropdown-item>
        </b-nav-item-dropdown>
        </b-navbar-nav>
    </div>
    </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.main{
    background-color: #e2e2e2;
}
.child{
    width: 50%;
    float: left;
}
.twochilds{
    width: 25%;
    float: left;
}
</style>