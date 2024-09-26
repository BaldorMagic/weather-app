<template>
  <div class="details">
    <div>Feels like: 22&deg;C</div>
    <div>Humidity: 40%</div>
    <div>Wind Speed: 5 m/s</div>
  </div>

</template>
<style scoped>
.details {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}

.details > div {
  padding: 20px;
  background-color: #f1f1f1;
  margin: 10px;
  flex: 1;
  border-radius: 5px;
  text-align: center;
  min-height: 45px;
}

@media (max-with: 768px){
}
</style>