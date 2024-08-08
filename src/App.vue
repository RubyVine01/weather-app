<script setup>

</script>

<template>
  <div class="wrapper">
    <h1>Приложение погоды</h1>
    <p>Узнать погоду в вашем городе</p>
    <input type="text" placeholder="Введите город">
    <button>Узнать погоду</button>
  </div>
</template>

<style scoped>
.wrapper {
  width: 900px;
  height: 500px;
  border-radius: 50px;
  background: #1f0f24;
  padding: 20px;
  text-align: center;
  color: white;
}

.wrapper h1 {
  margin-top: 50px;

}

.wrapper p {
  margin-top: 20px;
}


.wrapper input {
  margin-top: 30px;
  background-color: transparent;
  border: 0;
  border-bottom: 2px solid #110813;
  color: white;
  font-size: 5px 8px;
  outline: none;
}

.wrapper input:focus {
  border-bottom-color: #6e2d7d;
}

.wrapper button {
  margin-left: 20px;
  background: #e3bc4b;
  border-radius: 10px;
  border: 2px solid #b99935;
  color: white;
  padding: 10px 15px;
  margin-left: 20px;
  cursor: pointer;
  transition: transform 500ms ease;
}

.wrapper button:hover {
  transform: scale(1.1) translateY(-5px);
}
</style>
