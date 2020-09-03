<template>
  <div class="block-banner">
    <div class="container">
      <h1>Bring your ideal to life</h1>
    </div>
<!--    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#fff" fill-opacity="1" d="M0,256L48,229.3C96,203,192,149,288,154.7C384,160,480,224,576,218.7C672,213,768,139,864,128C960,117,1056,171,1152,197.3C1248,224,1344,224,1392,224L1440,224L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>-->
  </div>
</template>

<style>
  .block-banner {
    @apply flex items-center min-h-screen text-white;

    background: linear-gradient(180deg, #ff1a7d 0%, #008aff 100%), url("../../static/images/banner.jpg") center fixed no-repeat;
    background-blend-mode: multiply;
  }

  .block-banner .container {
    @apply w-full h-full object-cover;
  }

  .block-banner svg {
    @apply absolute inset-x-0 bottom-0;

  }
</style>
