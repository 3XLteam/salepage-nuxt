<template>
  <div class="block-services">
    <div class="content">
      <hgroup>
        <p>OUR SERVICES</p>
        <h2>OUR SERVICES</h2>
      </hgroup>

      <div class="list">
        <div class="item" v-for="list in 6">
          <h3>What is Lorem Ipsum?</h3>
          <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  .block-services {
    @apply bg-white text-black py-20;
  }

  .block-services .list {
    @apply grid grid-cols-3 gap-8;
  }


</style>
