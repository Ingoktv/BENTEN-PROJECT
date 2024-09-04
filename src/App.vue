<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import MyNav from './components/MyNav.vue'
import MyCard from './components/MyCard.vue'
import MyFooter from './components/MyFooter.vue';
</script>

<template>

  <header>
    
    <MyNav/>
    
    
   
    <!-- <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" /> -->

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>
 

  <main>
    
    <div class="grid-container">
      <h1>12 เอเลี่ยนใน BEN10</h1>
    <MyCard />

    </div>
  </main>
  <footer>
  <MyFooter />
  </footer>

</template>

<style scoped>
h1 {
  color: grey;
}
main {
  display: flex;
  justify-content: center;
  align-items: center;
}

/* header {
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
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
} */
</style>
