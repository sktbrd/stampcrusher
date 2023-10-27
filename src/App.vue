<template>
  <div>
    <h1 style="color: black;">Put out bids on commissioned art by artists that can't be easily contacted</h1>
    <div class="button-container">
      <button @click="showAlert" style="background-color: blue;" class="custom-button">
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

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// Define the function to show the alert
const showAlert = () => {
  alert('I always knew...');
}
</script>

<style scoped>
.custom-button {
  border: none;
  background-color: transparent;
  padding: 0;
  margin: 0;
  cursor: pointer;
  border-radius: 10px;
  padding: 10px;
}

.button-image {
  width: 100%;
  height: auto;
  object-fit: cover;
  border: none;
  padding: 0;
  margin: 0;
}

.button-container {
  position: absolute;
  top: 20px;
  right: 20px;
}
</style>
