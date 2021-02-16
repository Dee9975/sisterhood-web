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
  #app {

  }
</style>
