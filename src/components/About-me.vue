<template>
    <section class="about">
      <h2>About me</h2>
      <div class="me" v-for="me in me" :key="me.id">
        <h3>{{ me.position }}</h3>
        <p>{{ me.name }}</p>
        <p>{{ me.description }}</p>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    data() {
      return {
        me: [
          { id: 1, position: "  ", name: "I am currently studying at Kasetsart University, Kamphaeng Saen Campus. I am seeking an internship as a Front End or Back End development. I am interested in interning at your company to apply my knowledge in contributing to the organization's development. This opportunity will help me gain additional training and experience beyond what I have learned in the classroom. If assigned any tasks, I will do my utmost to achieve effective results.", description: "   " },
        ],
      };
    },
  };
  </script>
  
  <style lang="scss">
  .about {
    background-color: #ffffff;
    padding: 20px;
    margin-top: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  
    h2 {
      font-size: 22px;
      margin-bottom: 15px;
    }
  
    .me {
      margin-bottom: 15px;
      h3 {
        margin: 0;
        font-size: 18px;
      }
      p {
        margin: 5px 0;
      }
    }
  }
  </style>
  