<template>
    <div class="welcome-screen"> 
      <div class="content">
        <h1>PersonaLens</h1>
        <p>Энэхүү пдатформ нь<br> 
           таны бие хүний хэв<br> 
           шинжийг тодорхойлох<br> 
           мобайл шийдэл юм.
        </p>
        <button class="get-started" @click="onStart">Get started</button>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      onStart() {
        // Navigate to the next screen or trigger desired logic
        console.log('Get started clicked!');
      }
    }
  }
  </script>
  
  <style scoped>
  .welcome-screen {
    display: flex;
    justify-content: center; 
    align-items: center; 
    height: 100vh;
    background-color: #5D8A7B; 
    font-family: 'Arial', sans-serif; 
  }
  
  .content {
    text-align: center; 
    background-color: #C8D8E4; 
    padding: 40px;
    border-radius: 10px; 
  }
  
  h1 {
    color: #2C3E50; 
    margin-bottom: 20px; 
  }
  
  p {
    color: #34495E; 
    line-height: 1.6; 
    margin-bottom: 30px; 
  }
  
  .get-started {
    background-color: #27AE60; 
    color: white;
    padding: 15px 30px;
    border: none;
    border-radius: 5px;
    font-size: 18px; 
    cursor: pointer; 
  }
  </style>