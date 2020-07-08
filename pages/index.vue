<template>
  <div class="container">
      <div class="flex space-x-8 text-2xl">
     <nuxt-link to='/me'>javier</nuxt-link> 
     <nuxt-link to='/blog'>blog</nuxt-link> 
     <nuxt-link to='/links'>links</nuxt-link> 
     <nuxt-link to='/books'>libros</nuxt-link> 
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

</style>
