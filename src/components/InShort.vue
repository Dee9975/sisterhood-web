<template>
  <div class="container-fluid in-short">
    <div class="container">
      <div class="row content-wrapper">
        <div class="col-md-6">
          <span class="in-short-title">In short</span>
          <div class="spacer"></div>
          <div class="description-wrapper">
            <span class="in-short-description">I have more than 10 years of professional digital design experience, working in pharma, startup, insurance, real estate, fin-tech, cosmetic industries, doing so as an employee, freelancer, consultant and a friend.</span>
            <br/>
            <br/>
            <span class="in-short-description">Passionate about consulting startups, doing design work for organizations with the mission of building a better and more sustainable world.</span>
            <br/>
            <br/>
            <span class="in-short-description">Love to solve unsolvable problems, do a strong UX work and dive into moving and colorful UI.</span>
          </div>
        </div>
        <div class="col-md-6">
          <div class="row">
            <div class="col-6">
              <span class="caps-title">DESIGNING IN</span>
              <br/>
              <span class="explanation">Sketch, PS, Ai, In</span>
              <div class="small-spacer"></div>
              <span class="caps-title">Prototyping in</span>
              <br/>
              <span class="explanation">Invision and whatever you’ve got</span>
              <div class="small-spacer"></div>
              <span class="caps-title">On my way to learn</span>
              <br/>
              <span class="explanation">Drawing in Procreate</span>
              <div class="small-spacer"></div>
              <span class="caps-title">Listening to</span>
              <br/>
              <span class="explanation">Progressive metal and meditative sounds</span>
            </div>
            <div class="col-6">
              <span class="caps-title">Moving in</span>
              <br/>
              <span class="explanation">Principle, bits in AE</span>
              <div class="small-spacer"></div>
              <span class="caps-title">Can also rock on</span>
              <br/>
              <span class="explanation">Squarespace, Wordpress</span>
              <div class="small-spacer"></div>
              <span class="caps-title">Listening to</span>
              <br/>
              <span class="explanation">Marvel movies</span>
              <div class="small-spacer"></div>
              <span class="caps-title">Struggle with</span>
              <br/>
              <span class="explanation">Cleaning after my kids and avoiding snails in my garden</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InShort"
}
</script>

<style scoped>
  .in-short {
    background-color: #EEF2F5;
  }

  .in-short-title {
    font-size: 32px;
    font-weight: bold;
  }

  .description-wrapper {
    width: 400px;
  }

  .caps-title {
    text-transform: uppercase;
    font-weight: lighter;
    font-size: 14px;
  }

  .explanation {
    font-weight: bold;
    font-size: 14px;
  }

  .spacer {
    height: 58px;
  }

  .small-spacer {
    height: 32px;
  }

  .in-short-description {
    font-size: 16px;
    font-weight: lighter;
  }

  .content-wrapper {
    margin-top: 64px;
    padding-top: 240px;
    padding-bottom: 240px;
  }
</style>
