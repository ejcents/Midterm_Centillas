<template>
  <div class="container">
    <h1>Welcome</h1>
    <p class="name">Efren Jacob Centillas BSIT-3</p>
  </div>
</template>

<script>
export default {
  name: 'Home',
};
</script>

<style scoped>
body {
  background-image: url('path-to-your-background-image');
  background-size: cover;
  background-position: center;
  margin: 0;
  height: 100vh;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100%;
  color: blue;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

h1 {
  font-size: 2.5em;
  margin-bottom: 20px;
}

.name {
  font-size: 1.5em;
}

.course {
  font-size: 1.2em;
}
</style>