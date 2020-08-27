<template>
  <div id="root">
    <!--Header-->
    <Header />

    <!--Main-->
    <main>
      <Banner />
      <Solution />
      <AboutUs />
      <Services />
    </main>

    <!--Footer-->
    <Footer />

  </div>

</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
  #root {
    @apply flex flex-col min-h-screen;

    background-color: #654dd1;
  }
</style>
