<template>
  <div>
    <h1>Games</h1>

    <div style="margin-bottom: 30px;">
      The following are the key projects I've been involved in throughout my career.
    </div>

    <ProjectsList v-bind:projects="projects" />

    <h3>Is that all there is?</h3>
    <div>
      Far from it! You can check out all my game jams and side projects on <a target="_blank" href="https://neowedge.itch.io">my <span class="fa fa-gamepad" />itch.io</a>.<br />
      Over <strong>40 games</strong> waiting for you!
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import ProjectsList from "@/components/ProjectsList.vue";
import gameProjectsData from "@/data/GameProjectsData.ts";

export default Vue.extend({
  name: "GameProjects",
  components: {
    ProjectsList,
  },
  data: function () {
    return {
      projects: gameProjectsData,
    };
  },
});
</script>
