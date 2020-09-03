<template>
  <header>
    <div class="container">
      <!--Logo-->
      <a href="/">
        <img class="logo" src="https://via.placeholder.com/80x80" alt="Logo"/>
      </a>

      <!--Menu-->
      <nav>
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/">Project</a></li>
          <li><a href="/">About us</a></li>
          <li><a href="/">Services</a></li>
          <li><a href="/">Blog</a></li>
        </ul>
      </nav>
      </div>
  </header>
</template>

<style>
  header .container {
    @apply fixed flex items-center justify-between py-3 inset-x-0 text-white;
  }

  .logo {
    @apply rounded-full;

    max-height: 70px;
  }

  nav ul li {
    @apply inline-block ml-4;
  }
</style>
