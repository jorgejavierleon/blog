<template>
  <div class="p-6 md:p-10 sm:px-6 sm:py-10 lg:px-0">
    <div> 
     <nuxt-link to='/'>home</nuxt-link> 
       / links
    </div> 
    <h1 class="py-6 font-medium">Links</h1>
    <p>Esta es una lista de recursos que he ido acumulnado en el tiempo y que 
      encuentro útil tener a mano. Me funciona tambien como lista de cosas que 
      quiere leer después.
    </p>
    <h3 class="inline-block pt-5 font-medium">
      <span class="inline-block align-middle"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M20 6a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6c0-1.1.9-2 2-2h7.41l2 2H20zM4 6v12h16V8h-7.41l-2-2H4z"/></svg></span>
      Laravel
    </h3>
    <ul>
      <li><a href="">Documentación</a></li>
      <li><a href="">Laracast</a></li>
      <li><a href="">Laravel news</a></li>
    </ul>
    <h3>
      <span class="inline-block align-middle"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M20 6a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6c0-1.1.9-2 2-2h7.41l2 2H20zM4 6v12h16V8h-7.41l-2-2H4z"/></svg></span>
      Vim
    </h3>
    <ul>
      <li><a href="">Vim cheats</a></li>
      <li><a href="">Videos</a></li>
      <li><a href="">Tmux</a></li>
      <li><a href="">Coc</a></li>
      <li><a href="">Plugins</a></li>
    </ul>
  </div>
</template>

<style>
h3 {
  @apply inline-block; 
  @apply pt-10;
  @apply font-medium;
  @apply mb-2;
}
ul{
  @apply list-disc; 
  @apply list-inside;
}

</style>
