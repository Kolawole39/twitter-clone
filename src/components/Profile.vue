<template>
  <div class="section">
    <div class="container">
      <div class="columns">
        <div class="column is-10">
          <div class="card-profile card">
            <div class="header">
              <div class="avatar">
                <img
                  src="https://randomuser.me/api/portraits/women/67.jpg"
                  alt=""
                />
              </div>
            </div>
            <div class="card-body">
              <div class="user-meta has-text-centered">
                <h3 class="username">Helen Miller</h3>
                <h5 class="position">Accountant</h5>
              </div>
              <div class="action has-text-centered">
                <p>
                  Helen Miller is an accountant at the Acme Inc comany. She
                  works very hard.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Profile"
};
</script>

<style lang="css">
.columns {
  margin-top: 0;
}

.section {
  background-color: #ededed;
  min-height: 100vh;
  position: relative;
}
.section .card-profile {
  border-radius: 6px;
  overflow: hidden;
  max-height: 380px;
  margin: 0 auto;
}
.section .card-profile .header {
  height: 120px;
  background: #7f00ff;
}
.section .card-profile .header .avatar {
  width: 80px;
  height: 100%;
  position: relative;
  margin: 0 auto;
}
.section .card-profile .header .avatar img {
  display: block;
  border-radius: 50%;
  position: absolute;
  bottom: -42px;
  border: 4px solid white;
}
.section .card-profile .card-body {
  padding: 30px;
}
.section .card .card-body .user-meta {
  padding-top: 20px;
}
.section .card .card-body .user-meta .username {
  font-size: 18px;
  font-weight: 600;
}
.section .card .card-body .user-meta .position {
  font-size: 90%;
  color: #7f00ff;
}
.section .card .user-bio {
  padding-top: 8px;
  font-size: 92%;
  color: #999;
}
.section .card .action {
  padding-top: 20px;
}
.section .card .action .button {
  padding: 16px 20px 16px 20px;
  background: #7f00ff;
  border-color: #7f00ff;
  color: white;
  border-radius: 100px;
  transition: opacity 0.3s;
}
.section .card .action .button:hover {
  opacity: 0.7;
}

.link-button {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background: #7f00ff;
  position: absolute;
  bottom: 20px;
  right: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: all 0.4s;
}
.link-button img {
  width: 32px;
  height: 32px;
  display: block;
}
.link-button:hover {
  transform: scale(1.1) rotate(180deg);
  background: #00d1b2;
}
</style>
