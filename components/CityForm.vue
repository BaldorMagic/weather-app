<template>
  <form>
    <input type="text" id="city-input" placeholder="Enter City">
    <input type="submit" value="Get Weather">
  </form>
</template>
<style scoped>
form {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 20px;
}

form input[type="text"] {
  padding: 10px;
  border: none;
  outline: none;
  font-size: 18px;
  width: 60%;
}

form input[type="submit"] {
  background-color: #007bff;
  color: #fff;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  font-size: 18px;
  cursor: pointer;
  outline: none;
  transition: background-color .3s ease;
}

form input[type="submit"]:hover {
  background-color: #0062cc;
}

@media (max-width: 768px) {
  form {
    flex-direction: column;
  }

  form input[type="text"]{
    width: 100%;
    margin-bottom: 10px;
  }
}
</style>