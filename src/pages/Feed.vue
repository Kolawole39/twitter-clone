<template>
  <div class="columns">
    <div class="column is-3">
      <div class="mt-6">
        <Menu />
      </div>
    </div>
    <div class="column is-5 mt-4">
      <h3 class="title">Latest Tweets</h3>
      <CreateTweet />
      <hr />
      <div class="mt-3">
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

export default {
  name: "Feed",
  components: {
    Tweet,
    CreateTweet,
    Menu,
    Users
  }
};
</script>
