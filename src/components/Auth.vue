<template>
  <div id="auth">
    <h1>AUTH PAGE</h1>
      <md-avatar class="md-avatar-icon md-accent">
        <img src="../assets/logo.png" alt="Avatar">
      </md-avatar>
    <md-toolbar>
      <h1 class="md-title">My Title</h1>
    </md-toolbar>

    <div class="main-content">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, rerum? Error sunt, aperiam dolores, atque expedita molestiae tenetur. Quis eveniet accusamus velit explicabo adipisci reiciendis modi eaque quas, officia excepturi.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'auth',
  data () {
    return {
      user: {
        'username': '',
        'password': ''
      }
    }
  }
}
</script>
