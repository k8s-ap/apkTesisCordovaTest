<template>
  <v-app>
    <ToolBar/>
    <v-content>
      <Monitoreo/>
    </v-content>
  </v-app>
</template>

<script>
import ToolBar from './components/ToolBar';
import Monitoreo from './components/Monitoreo';

export default {
  name: 'App',
  components: {
     ToolBar,Monitoreo
  },
  data: () => ({
    //
  }),
};
</script>
