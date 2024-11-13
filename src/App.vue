<template>
  <div id="app" class="container">
    <Header />
    <AboutMe />
    <Experience />
    <Education />
    <Skill />
    <Language />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Experience from "./components/Experience.vue";
import Education from "./components/Education.vue";
import Skill from "./components/Skill.vue";
import Language from "./components/Language.vue";
import AboutMe from "./components/About-me.vue";

export default {
  components: {
    Header,
    AboutMe,
    Experience,
    Education,
    Skill,
    Language,
  },
};
</script>

<style lang="scss">
.container {
  max-width: 576px;
  margin: auto;
  padding: 20px;
}

@media (min-width: 576px) {
  .container {
    max-width: 800px;
  }
}
</style>