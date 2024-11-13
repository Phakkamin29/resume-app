<template>
    <section class="experience">
      <h2>Project / Additional Trainining</h2>
      <div class="job" v-for="job in jobs" :key="job.id">
        <h3>{{ job.position }}</h3>
        <p>{{ job.project }}</p>
        <p>{{ job.description }}</p>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    data() {
      return {
        jobs: [
          { id: 1, position: "Mini-Project Internet Application for Commerce", project: "Social Coffee Business Website.", description: "Build a community coffee shop website from a business model canvas." },
          { id: 2, position: "Mini-Project Fundamentals of Database System", project: "Movie Ticket Bookking Database System.", description: "Create a database to support the storage of movie ticket booking data for use in developing business systems." },
          { id: 3, position: "Mini-Project Systems Analysis and design", project: "Body Balance Monitoring System (Homeosis Health).", description: "Create a database to support the storage of movie ticket booking data for use in developing business systems." },
          { id: 4, position: "Linux & Docker Training Program", project: "    ", description: "Participate in Linux & Docker training to improve your learning and work." },
          { id: 5, position: "Google Data Analytics Training Program", project: "   ", description: "Foundation: Data/ Data Everywhere." },
        ],
      };
    },
  };
  </script>
  
  <style lang="scss">
  .experience {
    background-color: #ffffff;
    padding: 20px;
    margin-top: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  
    h2 {
      font-size: 22px;
      margin-bottom: 15px;
    }
  
    .job {
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
  