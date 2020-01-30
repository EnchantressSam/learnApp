<template>
  <v-app id="app">
    <div id="nav">
      <TopNav />
    </div>
      <v-content>
        <v-container>
          <router-view/>
        </v-container>
    </v-content>
  </v-app>
</template>
<script>
import TopNav from './components/TopNav.vue'
export default {
  components: {
    TopNav
  }
}
</script>
