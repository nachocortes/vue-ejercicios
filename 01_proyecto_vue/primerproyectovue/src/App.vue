<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
    <div class="container">

      <header>
        <img alt="Vue logo" class="logo" src="./assets/bootstrap.scss" width="125" height="125" />

        <div class="wrapper">
          <HelloWorld msg="You did it!" />
        </div>

      </header>

      <main>
        <TheWelcome />
      </main>
        <button class="btn btn-secondary">jhgjhgh</button>
        <button class="btn btn-primary">jhgjhgh</button>
    </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;

  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
