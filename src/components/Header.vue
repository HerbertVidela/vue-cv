<template>
  <div id="header">
    <div class="left-side">
      <div class="first-name">Herbert</div>
      <div class="last-name">Videla</div>
      <div class="title">Front-end developer</div>
    </div>
    <div class="right-side">
      <div class="profile-pic-wrapper">
        <img src="../assets/profile-pic.png" class="profile-pic" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Header"
});
</script>

<style scoped>
#header {
  align-items: center;
  background-color: #f3f3f3;
  border-top: 5px solid #f2ab52;
  display: flex;
  justify-content: center;
  padding: 40px 0;
}

.left-side {
  padding-right: 450px;
}

.first-name {
  font-weight: 500;
  font-size: 60px;
  line-height: 50px;
  padding-bottom: 15px;
  letter-spacing: 10px;
}

.last-name {
  font-size: 60px;
  font-weight: 200;
  line-height: 50px;
  padding-bottom: 25px;
  letter-spacing: 10px;
}

.title {
  font-size: 16px;
  line-height: 16px;
}

.profile-pic-wrapper {
  width: 150px;
  height: 150px;
  border-radius: 100px;
  overflow: hidden;
}

.profile-pic {
  width: 160px;
  margin-top: -10px;
}
</style>
