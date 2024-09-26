<script setup>
import WeatherDetails from './WeatherDetails.vue'
</script>
<template>
  <div id="weather-data">
    <div class="icon">
      <img src="http://openweathermap.org/img/wn/01d.png" alt="Weather icon">
    </div>
    <div class="temperature">22&deg;C</div>
    <div class="description">Sunny</div>
    <WeatherDetails />
  </div>
</template>
<style scoped>
.icon img {
  width: 100px;
  height: 100px;
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center center;
}

.temperature {
  font-size: 48px;
  font-weight: bold;
  margin: 20px 0;
}

.description {
  font-size: 24px;
  margin-bottom: 20px;
}
</style>