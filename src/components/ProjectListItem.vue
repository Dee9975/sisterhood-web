<template>
  <div class="project-item m-0"
       :style="{'background-image': 'url(' + require('../assets/' + project.image) + ')'}"
       @mouseover="hover = true"
       @mouseleave="hover = false">
    <div class="blur-box"></div>
    <span class="project-title" v-if="hover">{{project.title}}</span>
    <div class="project-subtitle">
      <span class="project-name">{{project.projectName}}</span>
      <span v-if="project.type"> | {{project.type}}</span>
      <br/>
      <span>Branding, App Design I 2020</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProjectListItem",
  props: ["project"],
  data() {
    return {
      hover: false,
    }
  },
}
</script>

<style scoped>
  .project-item {
    width: 100%;
    height: 280px;
    background-repeat: no-repeat;
  }

  .project-subtitle {
    position: absolute;
    bottom: 32px;
    left: 32px;
    font-size: 16px;
    font-weight: lighter;
    color: white;
    text-align: left;
  }

  .blur-box {
    width: 100%;
    height: 280px;
    background-color: #263044;
    opacity: 40%;
  }

  .blur-box:hover {
    opacity: 80%;
  }

  .project-title {
    position: absolute;
    top: 16px;
    left: 32px;
    padding-right: 24px;
    color: white;
    font-size: 32px;
    font-weight: bold;
  }

  .project-name {
    font-weight: bold;
  }
</style>
