<template>
  <div class="container">
      The first practice for routes Udemy
      <hr>
      <h1>Welcome</h1>
      <button @click="productos">Ir a productos</button>
  </div>
</template>

<script>
  export default {
    methods : {
      productos:function(){               
        this.$router.push('products')
      }
    }
  }
</script>