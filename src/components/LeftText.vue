<template>
  <div class="left-text p-0 m-0"></div>
</template>

<script>
export default {
name: "LeftText"
}
</script>

<style scoped>
  .left-text {
    min-height: 798px;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    align-content: stretch;
    background-color: #EEF2F5;
    text-align: left;
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

  .title-container {
    text-align: left;
    width: 415px;
  }

  .name {
    position: absolute;
    top: 16px;
    text-align: right;
  }
</style>
