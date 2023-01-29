<template>
  <NavComponent />
  <router-view/>
</template>



<script lang="ts">
import { defineComponent } from 'vue';
import NavComponent from '@/components/NavComponent.vue';


export default defineComponent({
  components: { NavComponent },
  setup() {
    name: 'App';
    components: {
      NavComponent
    }
    
  },
})
</script>



<style>
#app {
  color: #2c3e50;
}


</style>
