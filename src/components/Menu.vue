<template>
  <article class="m-4 is-primary">
    <p class="panel-heading has-background-primary has-text-white">
      Tweeter-Hasura
    </p>
    <router-link class="panel-block is-active" to="/dashboard">
      <span class="panel-icon">
        <i class="fas fa-user" aria-hidden="true"></i>
      </span>
      Profile
    </router-link>
    <a class="panel-block">
      <span class="panel-icon"> <i class="fas fa-sign-out-alt"></i> </span>
      Logout
    </a>
  </article>
</template>

<script>
export default {
  data() {
    return {
      isActive: true
    };
  },
  name: "Menu"
};
</script>
