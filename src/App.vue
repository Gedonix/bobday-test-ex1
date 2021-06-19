<template>
  <v-app>    
    <v-main>
      <question />
    </v-main>
  </v-app>
</template>

<script>
import Question from './components/Question.vue'

export default {
  name: 'App',
  components: {    
    Question    
  },
};
</script>
