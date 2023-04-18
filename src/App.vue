<template>
  <div class="container">

    <headerComponent />
    <mainComponent />
    <FooterComponent />
    
  </div>
</template>

<script>
import headerComponent from './components/headerComponent.vue';
import mainComponent from './components/mainComponent.vue'; 
import footerComponent from './components/footerComponent.vue';
import FooterComponent from './components/footerComponent.vue';

export default {
  name: 'App',
  components: {
    headerComponent,
    mainComponent,
    FooterComponent
}
}
</script>

<style lang="scss" scoped></style>