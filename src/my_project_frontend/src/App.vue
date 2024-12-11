<template>
   <div class="bg-gray-400">
  <Header></Header>
  <Calculator></Calculator>
</div>
</template>

<script>
import Calculator from './components/Calculator.vue';
import Header from './components/Header.vue';

 export default {
  name: "App",
  components: {
    Header,
    Calculator,
  },
 };
</script>