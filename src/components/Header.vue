<template>
  <div class="container-fluid app-header">
    <div class="container">
      <div class="bring-top">
          <span class="name">Elina Frolova</span>
          <span class="divider"> I </span>
          <span class="job-title">Digital designer</span>
          <div class="title-container">
            <span class="title">Hello fellow Earthlings ✌️</span>
            <span class="subtext">I am Elina - Digital Designer, based in Copenhagen and World Wide Web</span>
          </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-7 p-0"></div>
      <div class="col-sm-5 p-0 right-image"></div>
    </div>

  </div>
</template>

<script>

export default {
  name: "Header",
  components: {},
  comments:{

  }
}
</script>

<style scoped>
  .bring-top {
    padding-top: 16px;
    position: absolute;
    height: 798px;
  }

  .title-container {
    margin-top: 244px;
    text-align: left;
    width: 415px;
  }

  .title {
    font-size: 36px;
    font-weight: bold;
    text-align: left;
    /*flex: 1 1 auto;*/
  }

  .subtext {
    font-size: 36px;
    font-weight: lighter;
    text-align: left;
  }

  .name {
    font-weight: bold;
  }

  .divider {
    font-size: 18px;
  }

  .name, .job-title {
    font-size: 16px;
  }

  .job-title, .divider {
    font-weight: lighter;
  }

  .app-header {
    position: relative;
    background-color: #EEF2F5;
  }

  .right-image {
    height: 798px;
    background-repeat: no-repeat;
    overflow: visible;
    position: relative;
    background-image: url("../assets/image.png");
    background-position-x: -270px;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: flex-start;
    align-items: center;
    align-content: stretch;
    background-color: #EEF2F5;
    text-align: left;
  }
</style>
