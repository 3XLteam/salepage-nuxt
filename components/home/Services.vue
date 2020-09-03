<template>
  <div class="block-services">
    <div class="container">
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
    @apply bg-white text-black py-40;
  }

  .block-services .list {
    @apply grid grid-cols-3 gap-8;
  }

  .block-services .list .item {
    padding: 2rem;
    border: 1px solid #ccc;
    transition: all 0.3s ease;
  }

  .block-services .list .item:hover {
    background-color: #008aff;
    color: #fff;
  }


</style>
