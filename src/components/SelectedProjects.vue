<template>
  <div class="container">
    <div class="row projects-row">
      <div class="col-sm-6">
        <span class="projects-title">Selected Projects</span>
      </div>
      <div class="col-sm-6">
        <span class="projects-subtitle">Daily I am working with UI and UX heavy projects, due to high confidentiality those cannot be displayed in my portoflio. But here you are able to see snipets of my past or freelance work where I try to experiment more with branding, bright colors and illustrations. </span>
      </div>
    </div>
    <ProjectList v-bind:projects="projects" class="projects-list"/>
  </div>
</template>

<script>
import ProjectList from "@/components/ProjectList";
export default {
name: "SelectedProjects",
  components: {ProjectList},
  data() {
    return {
      projects: [
        {
          id: 1,
          image: "sisterhood.png",
          projectName: "Mighty girls",
          type: "Collaboration project",
          title: "An app that celebrates mighty woman in history",
          smallTitle: "This is the small title that is always shown",
        },
        {
          id: 2,
          image: "def-BEC.png",
          projectName: "BEC",
          type: "Collaboration project",
          title: "Digital transformation in banking",
          smallTitle: "This is the small title that is always shown",
        },
        {
          id: 3,
          image: "def-Beer.png",
          projectName: "The uncharted Brewing",
          title: "Packaging design for the series of beers",
          smallTitle: "This is the small title that is always shown",
        },
        {
          id: 4,
          image: "def-5AM.png",
          projectName: "5AM",
          type: "Collaboration project",
          title: "Branding exercise for amaranth oil producer",
          smallTitle: "This is the small title that is always shown",
        },
        {
          id: 5,
          image: "def-query.png",
          type: "Collaboration project",
          projectName: "getQueried app",
          title: "Opinion polls made available to everyone",
          smallTitle: "This is the small title that is always shown",
        },
        {
          id: 6,
          image: "def-SWTF.png",
          type: "Collaboration project",
          projectName: "Seriously WTF",
          title: "The only magazine that travels the world",
          smallTitle: "This is the small title that is always shown",
        },
      ],
    }
  },
}
</script>

<style scoped>
  .projects-title {
    font-size: 32px;
    font-weight: bold;
  }

  .projects-row {
    margin-top: 64px;
  }

  .projects-subtitle {
    font-size: 14px;
    font-weight: lighter;
    color: #263044;
  }

  .projects-list {
    margin-top: 64px;
  }
</style>
