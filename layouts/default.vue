<template>
  <div>
    <Nuxt />
  </div>
</template>


<style>
  html {
    font-size: 62.5%;
  }

  body {
    font-family: 'Poppins', sans-serif;
    font-size: 1.6rem;
  }

  /* Heading */

  h1 {
    @apply font-bold tracking-widest;

    font-size: 5rem;
  }

  h2 {
    @apply font-bold tracking-widest;

    font-size: 4rem;
  }

  h3 {
    @apply font-bold tracking-widest;

    font-size: 2rem;
  }

  /* hgroup */
  hgroup {
    @apply mb-8;
  }

  .container {
    @apply px-10 max-w-full mx-auto;
  }

  @-webkit-keyframes zoomSize3 {
    0% {
      opacity: 0;
      height: 0;
      width: 0;
    }
    50% {
      opacity: 1;
      height: 1.625rem;
      width: 1.625rem;
    }
  }
  @keyframes zoomSize3 {
    0% {
      opacity: 0;
      height: 0;
      width: 0;
    }
    50% {
      opacity: 1;
      height: 1.625rem;
      width: 1.625rem;
    }
  }

</style>
