<template>
  <div class="columns">
    <div class="column is-3">
      <div class="mt-6">
        <Menu />
      </div>
    </div>
    <div class="column is-5 mt-4">
      <span class="columns">
        <p class="mt-2">
          <a @click="$router.go(-1)"><i class="fas fa-arrow-left"></i></a>
        </p>
        <h3 class="title ml-3">
          Profile
        </h3>
      </span>
      <Profile />
      <hr />
      <CreateTweet />
      <hr />
      <div class="mt-3">
        <h3 class="title is-3">Your Tweets</h3>

        <Tweet />
        <Tweet />
        <Tweet />
        <Tweet />
        <Tweet />
        <Tweet />
        <Tweet />
        <Tweet />
        <Tweet />
      </div>
    </div>
    <div class="column is-3 mt-4">
      <h3 class="title">Other Users</h3>
      <div class="mt-3 card p-2">
        <Users />
        <Users />
        <Users />
      </div>
    </div>
  </div>
</template>

<script>
import Tweet from "../components/Tweet";
import CreateTweet from "../components/CreateTweet";
import Menu from "../components/Menu";
import Users from "../components/Users";
import Profile from "../components/Profile";

export default {
  name: "Dashboard",
  components: {
    Tweet,
    CreateTweet,
    Menu,
    Users,
    Profile
  }
};
</script>
