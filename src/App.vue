<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
<div>
<h1> 
put out bids on commissioned art by artists that cant be easily contacted
</h1>
  <div class="button-container">
<button style="background-color: blue;" class="custom-button">
      Connect Your Butthole
    </button>
  </div>
</div>
  <div>
    <button class="custom-button">
      <img src="https://i.ibb.co/C56Q9Wj/image.png" alt="Image Placeholder" class="button-image">
    </button>
  </div>
</template>

<style scoped>
.custom-button {
  border: none;
  background-color: transparent;
  padding: 0;
  margin: 0;
  cursor: pointer;
  border-radius: 10px;
  padding: 10px
}

.button-image {
  width:100%; 
  height: auto; /* Set the height of the image */
  object-fit: cover; /* Ensure the image covers the entire button area */
  border: none;
  padding: 0;
  margin: 0;
}
</style>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.button-container {
  position: absolute;
  top: 20px; /* Adjust the top position as needed */
  right: 20px; /* Adjust the right position as needed */
}
</style>
