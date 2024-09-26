<script setup>
import CityForm from './components/CityForm.vue'
import WeatherData from './components/WeatherData.vue'


</script>

<template>
  <div class="container">
    <h1>Weather App</h1>
    <CityForm />
    <WeatherData />
  </div>
</template>

<style scoped>
.container {
  background-color: #fff;
  box-shadow: 0 0 20px rgba(0, 0, 0, .2);
  text-align: center;
  max-width: 600px;
  margin: 50px auto 0;
  border-radius: 5px;
  padding: 20px;
}
</style>
