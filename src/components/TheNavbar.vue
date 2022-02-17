<template>
    <div style="margin-bottom: 20px;">
  <b-navbar toggleable="lg" type="dark" variant="primary" style="height: 65px">
    <b-navbar-brand href="#" style="margin-left: 20px"><b-icon-linkedin></b-icon-linkedin></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
        <b-nav-item-dropdown text="FEED" right>
          <b-dropdown-item href="#">Item - 1</b-dropdown-item>
          <b-dropdown-item href="#">Item - 2</b-dropdown-item>
          <b-dropdown-item href="#">Item - 3</b-dropdown-item>
        </b-nav-item-dropdown>
        </b-navbar-nav>
      <b-navbar-nav>
        <b-nav-item href="#">NETWORK</b-nav-item>
        <b-nav-item href="#">JOBS</b-nav-item>
        <b-nav-item href="#">CHAT</b-nav-item>
        <b-nav-item href="#">NOTICES</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form>
        </b-navbar-nav>
        <span style="padding-left: 650px; font-size: 12px; color: white;">D. KARGAEV <br>(367 views today)</span>
        <b-navbar-nav>
        <b-nav-item href="#" style="padding-left: 10px;">OTHER</b-nav-item>
      </b-navbar-nav>
      
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>