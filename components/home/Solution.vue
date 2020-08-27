<template>
  <div class="block-solution">
    <div class="content">
      <hgroup>
        <p>OUR SERVICES</p>
        <h2>BEST SOLUTIONS</h2>
      </hgroup>

      <div class="list">
        <div class="item" v-for="list in 6">
          <h3>What is Lorem Ipsum?</h3>
          <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's</p>
        </div>
      </div>
    </div>

    <!--<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#fff" fill-opacity="1" d="M0,32L80,37.3C160,43,320,53,480,85.3C640,117,800,171,960,186.7C1120,203,1280,181,1360,170.7L1440,160L1440,0L1360,0C1280,0,1120,0,960,0C800,0,640,0,480,0C320,0,160,0,80,0L0,0Z"></path></svg>-->
  </div>
</template>

<style>
  .block-solution {
    @apply bg-white text-black py-20;
  }

  .block-services .list {
    @apply grid grid-cols-3 gap-8;
  }


</style>
