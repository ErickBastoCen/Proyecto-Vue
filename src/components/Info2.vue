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
      
    <a href="http://isclab.com.mx/" target="_blank" rel="noopener"> Contacto: contacto@isclab.com.mx </a>.

    </h3>
  </div>
</template>
