<template>
  <div class="main">
    <img class="logo" alt="Ivan logo" src="@/assets/logo.png">
    <h1> Coming Soon </h1>

  </div>
</template>

<script>
export default {
  name: 'ComingSoon',
  }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Sawarabi+Mincho&display=swap');
@keyframes fade-in {
0%{ opacity: 0; }
100%{opacity: 1;}
}

.main {
  display: flex-cloumn;
  align-items: center;
  justify-content: space-around;
  animation: fade-in 3s;
  font-family: 'Sawarabi Mincho', serif;
}

.logo {
      width: 100px;
      height: 100px;

  }

</style>
