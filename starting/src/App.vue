<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import Container from "./components/Container.vue";
import FormsContainer from "./components/FormsContainer.vue";
import Navigation from "./components/Navigation.vue";
</script>

<template>
  <div class="container">
    <Container>
      <Navigation></Navigation>
      <FormsContainer><div>forms will be here</div></FormsContainer>
    </Container>
  </div>
</template>

<style scoped>
.container {
}
</style>
