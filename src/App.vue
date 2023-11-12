<template>
  <div>
    <h1 class="text-center text-2xl mt-10"><strong>List of Contry</strong></h1>
    <CountryCatalog />
  </div>
</template>

<script>
import CountryCatalog from './components/CountryCatalog.vue';

export default {
  components: {
    CountryCatalog
  }
};
</script>