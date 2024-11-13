<template>
    <section class="language">
      <h2>Language</h2>
      <div class="lang" v-for="lang in lang" :key="lang.id">
        <h3>{{ lang.position }}</h3>
        <p>{{ lang.name }}</p>
        <p>{{ lang.description }}</p>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    data() {
      return {
        lang: [
          { id: 1, position: "  ", name: "English", description: "   " },
          { id: 2, position: "  ", name: "Thai", description: "   " },
        ],
      };
    },
  };
  </script>
  
  <style lang="scss">
  .language {
    background-color: #ffffff;
    padding: 20px;
    margin-top: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  
    h2 {
      font-size: 22px;
      margin-bottom: 15px;
    }
  
    .lang {
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
  