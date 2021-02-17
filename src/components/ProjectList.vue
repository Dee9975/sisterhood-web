<template>
  <div class="row">
    <div v-for="project in projects" :key="project.id" class="col-md-4 pb-4">
      <ProjectListItem v-bind:project="project"/>
    </div>
  </div>
</template>

<script>
import ProjectListItem from "@/components/ProjectListItem";
export default {
  name: "ProjectList",
  props: ["projects"],
  components: {
    ProjectListItem
  },
}
</script>

<style scoped>

</style>
