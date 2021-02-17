<template>
  <div id="app">
    <Header/>
    <SelectedProjects/>
    <InShort/>
    <Footer/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import SelectedProjects from "@/components/SelectedProjects";
import InShort from "@/components/InShort";
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    InShort,
    SelectedProjects,
    Header,
    Footer
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
  html, body {
    font-family: "Inter", sans-serif;
  }

  #app {
    font-family: "Inter", sans-serif;
  }
</style>
