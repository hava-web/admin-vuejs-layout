<template>
  <v-app id="inspire">
    <v-navigation-drawer
      v-model="drawer"
      app
    >
      <!-- Slide bar -->

    </v-navigation-drawer>

    <v-app-bar app> 
    <!-- Nav Bar -->
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>

      <v-toolbar-title>My Application</v-toolbar-title>
    </v-app-bar>

    <v-main>
      <!-- Content -->
      
    </v-main>
  </v-app>
</template>

<script>
  export default {
    data: () => ({ drawer: null }),
  }
</script>