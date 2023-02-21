<script setup>
import Inicio from './components/Inicio.vue'
import Info from './components/Info.vue'
import Info2 from './components/Info2.vue'
import Info3 from './components/Info3.vue'
import Info4 from './components/Info4.vue'
import Info5 from './components/Info5.vue'
</script>

<template>
  
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" />     
    <br />
    <br />
  </header>
  
  <body>
    <CENTER>
     <H1>
     LABORATORIO DE SISTEMAS Y APLICACIONES WEB
     </H1>
    </CENTER>
    <br />
    <br />
    <main>
      <Info /> 
      <br />

      <Info2 />
      

    </main>

    <br />
    <br />

    <Info3 />
    <br />
    <br />
    <Info4 />

  </body>

  <br />
  <br />

  <footer>
  <Info5 />
  </footer>
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
}
</style>

<img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />