<template>
  <div class="right-image p-0 m-0"></div>
</template>

<script>
export default {
name: "RightImage"
}
</script>

<style scoped>
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
