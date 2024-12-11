<template>
  <v-app>
    <v-app-bar flat class="border-b">
      <v-app-bar-title>Meu App</v-app-bar-title>
    </v-app-bar>

    <v-main>
      <v-container>
<h1 class="hidden-md text-h5 text-md-h1">DashBoard</h1>

        <div class="d-flex flex-column flex-md-row justify-space-between">
          <div
            class="w-100 pa-4 border rounded-lg elevation-3">
            teste
          </div>
          <div
            class="w-100 pa-4 border rounded-lg elevation-3">
            teste
          </div>
          <div
            class="w-100 pa-4 border rounded-lg elevation-3">
            teste
          </div>
        </div>
      </v-container>

      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue';
</script>
