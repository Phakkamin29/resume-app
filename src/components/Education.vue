<template>
    <section class="education">
      <h2>Education</h2>
      <div class="school" v-for="school in schools" :key="school.id">
        <h3>{{ school.degree }}</h3>
        <p>{{ school.university }}</p>
        <p>{{ school.years }}</p>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    data() {
      return {
        schools: [
          { id: 1, degree: "Bachelor's degree,Program in Computer Science", university: "Kasetsart University, Kamphaeng Saen Campus.", years: "June  2021 - Present" },
        ],
      };
    },
  };
  </script>
  
  <style lang="scss">
  .education {
    background-color: #ffffff;
    padding: 20px;
    margin-top: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  
    h2 {
      font-size: 22px;
      margin-bottom: 15px;
    }
  
    .school {
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
  