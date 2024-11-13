<template>
    <section class="skill">
      <h2>Skill</h2>
      <div class="tool" v-for="tool in tool" :key="tool.id">
        <h3>{{ tool.position }}</h3>
        <p>{{ tool.name }}</p>
        <p>{{ tool.description }}</p>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    data() {
      return {
        tool: [
          { id: 1, position: "  ", name: "C/C#", description: "   " },
          { id: 2, position: "  ", name: "MySQL", description: "   " },
          { id: 3, position: "  ", name: "JavaScript", description: "   " },
          { id: 4, position: "  ", name: "CSS", description: "    " },
          { id: 5, position: "  ", name: "HTML", description: "    " },
          { id: 6, position: "  ", name: "Docker", description: "    " },
          { id: 7, position: "  ", name: "Jupyter (Python)", description: "    " },
          { id: 8, position: "  ", name: "PHP", description: "    " },
          { id: 9, position: "  ", name: "Figma", description: "    " },
          { id: 10, position: "  ", name: "Sketch", description: "    " },
        ],
      };
    },
  };
  </script>
  
  <style lang="scss">
  .skill {
    background-color: #ffffff;
    padding: 20px;
    margin-top: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  
    h2 {
      font-size: 22px;
      margin-bottom: 15px;
    }
  
    .tool {
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
  