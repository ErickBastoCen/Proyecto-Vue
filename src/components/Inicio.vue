<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="blue">{{ msg }}</h1>
    <h3>
      Desarrollamos aplicaciones con fines de práctica, investigación y responsabilidad social.
      Buscamos el desarrollo de nuestros estudiantes a través de la creación de proyectos que sean útiles a la sociedad.

      <br />
      ¿Tienes un proyecto en mente? Compártelo con nosotros y buscaremos la manera de ayudarte.
      <br />
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
