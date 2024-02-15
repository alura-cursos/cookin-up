<script lang="ts">
import Banner from './components/Banner.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';
import Rodape from './components/Rodape.vue';

export default {
  components: { Banner, ConteudoPrincipal, Rodape }
}
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
  <Rodape />
</template>