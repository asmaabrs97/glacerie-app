<template>
  <v-layout class="rounded rounded-md">
    <v-app-bar>
            <v-img  src="/CodeVue-logo-removebg-preview.png" />
    </v-app-bar>


    <v-main class="d-flex align-center justify-center" style="min-height: 300px;">
      <slot />
    </v-main>
   
  </v-layout>
</template>

<script setup>


</script>

<style lang="scss" scoped>

</style>