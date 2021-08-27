<template>
  <v-app id="app">
     <app-nav>
      <ToolBar />
     </app-nav>
    <app-view>
      <router-view/>
    </app-view>
  </v-app>
</template>

<script>
import ToolBar from '@/components/ToolBar'
export default {
  name: 'App',
  components: {
    ToolBar
  },
  data() {
    return {}
  }
};
</script>
