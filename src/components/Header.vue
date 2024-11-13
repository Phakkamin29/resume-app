<template>
    <header class="header">
      <img src="https://i.postimg.cc/zGSdSXnR/temp-Imagekts-Hj-S.avif
      " alt="Profile Picture" class="profile-pic" />
      <div class="info">
        <h1>Phakkamin Srisawat</h1>
        <h2>Frontend Developer</h2>
        <p>📞 065-8268560</p>
        <p>📧 phakkamin.s@ku.th</p>
        <p>📍 27 Village No.5, Phailom Sub-district, Phachi District, Ayutthaya, 13140</p>
      </div>
    </header>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style lang="scss">
  .header {
    display: flex;
    align-items: center;
    padding: 20px;
    background-color: #DFD7D3;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  
    .profile-pic {
      width: 170px;
      height: 200px;
      border-radius: 0%;
      margin-right: 20px;
    }
  
    .info {
      h1 {
        margin: 0;
        font-size: 24px;
      }
      h2 {
        margin: 5px 0;
        font-size: 18px;
        color: gray;
      }
      p {
        margin: 5px 0;
      }
    }
  }
  </style>