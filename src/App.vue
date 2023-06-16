<script setup>
</script>

<template>
  <div class="container">
    <div class="barraLateral h-screen"></div>
    <main class="h-screen text-center w-100 py-10 md:mx-auto mx-2">
      <h1 class="md:my-8 my-5">Acesso não autorizado</h1>
      <p class="my-2 md:mt-5">Você não tem acesso a este conteúdo, verifique com seu gestor para a liberação</p>
      <v-img :width="300" :max-height="400" aspect-ratio="1" src="../public/acesso-negado.svg" class="my-2" ></v-img>
      <v-btn rounded="xl" color="#4b1441" class="text-white mb-10 mx-auto md:my-auto my-5">
        Voltar ao login
      </v-btn>
    </main>
  </div>
</template>

<style scoped>
.container {
  max-height: 100vh;
  display: flex;
  flex-direction: row;
}
.barraLateral {
  background-color: #4b1441;
  width: 15%;
}

main {
  font-family: 'Space Mono', monospace;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
