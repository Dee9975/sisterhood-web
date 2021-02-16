<template>
  <div class="container-fluid main-footer">
    <div class="container">
      <div class="row footer-wrapper">
        <div class="col-md-6">
          <span class="footer-text">If you want a collab, have a messy project you want me to solve or other fun stuff Send your email to:</span>
          <span> frolovaelina (at) gmail.com</span>
        </div>
        <div class="col-md-6">
          <div class="row justify-content-end">
            <div class="col-auto ig image"></div>
            <div class="col-auto linkedIn image"></div>
            <div class="col-auto dribble image"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
  .main-footer {
    background-color: #263044;
  }

  .footer-wrapper {
    padding-top: 32px;
    padding-bottom: 32px;
    color: white;
    font-size: 14px;
  }

  .footer-text {
    color: white;
    font-weight: bold;
  }

  .ig {
    background-image: url("../assets/footer-instagram.svg");
    padding-right: 50px;

  }

  .linkedIn {
    background-image: url("../assets/footer-linkedin.svg");
    padding-right: 50px;

  }

  .dribble {
    color: white;
    background-image: url("../assets/footer-dribbble.svg");
  }

  .image {
    width: 50px;
    height: 50px;
    text-align: right;
    background-repeat: no-repeat;
  }
</style>
