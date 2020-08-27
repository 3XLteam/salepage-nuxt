<template>
  <div class="block-about">
    <!--<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#ffffff" fill-opacity="1" d="M0,128L48,117.3C96,107,192,85,288,106.7C384,128,480,192,576,202.7C672,213,768,171,864,165.3C960,160,1056,192,1152,208C1248,224,1344,224,1392,224L1440,224L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path></svg>-->
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

    <!--<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#fff" fill-opacity="1" d="M0,192L60,197.3C120,203,240,213,360,208C480,203,600,181,720,154.7C840,128,960,96,1080,101.3C1200,107,1320,149,1380,170.7L1440,192L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path></svg>-->
  </div>
</template>
<style>
  .block-about {
    @apply py-20;

    background-color: #09f;
  }

</style>
