<template>
  <div id="body">
    <div class="left-side">
      <BasicInfo />
      <Education />
    </div>
    <div class="separator" />
    <div class="right-side">
      <WorkExperience />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import BasicInfo from "./BasicInfo.vue";
import Education from "./Education.vue";
import WorkExperience from "./WorkExperience.vue";

export default Vue.extend({
  name: "Body",
  components: {
    BasicInfo,
    Education,
    WorkExperience
  }
});
</script>

<style scoped>
#body {
  background-color: white;
  display: flex;
}

.left-side {
  padding-top: 80px;
}

.right-side {
  padding-top: 80px;
}

.separator {
  width: 1px;
  border-right: 1px solid gray;
  margin: 80px 0;
  min-height: 700px;
}
</style>
