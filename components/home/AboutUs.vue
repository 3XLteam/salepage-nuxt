<template>
  <div class="block-about">
    <div class="container">
      <hgroup>
        <p>ABOUT US</p>
        <h2>MY LOCATION</h2>
      </hgroup>

      <div class="map">
        <img src="../../static/images/bg-map.svg" alt="3XL team location">

        <span class="country"><i class="icon"></i> Việt Nam</span>
      </div>

      <div class="list grid gap-4 grid-cols-1 sm:grid-cols-4">
        <div class="item">
          <span>2+</span>
          <span>YEARS</span>
        </div>

        <div class="item">
          <span>2+</span>
          <span>PROJECTS</span>
        </div>

        <div class="item">
          <span>5+</span>
          <span>EMPLOYEE</span>
        </div>

        <div class="item">
          <span>1</span>
          <span>OFFICE</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  .block-about {
    @apply py-40 text-white;
  }

  .block-about .map {
    @apply relative;

    height: 700px;
  }

  .block-about .map img {
    @apply w-full h-full object-fill;
  }

  .block-about .map .country {
    @apply absolute;

    right: 25%;
    top: 48%;
    color: #ff1a7d;
    display: flex;
    align-items: center;
  }

  .block-about .map .icon {
    width: 30px;
    height: 30px;
    position: relative;
  }

  .block-about .map .icon::before {
    content: "";
    position: absolute;
    width: 10px;
    height: 10px;
    background-color: #ff1a7d;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
  }

  .block-about .map .icon::after {
    content: "";
    position: absolute;
    width: 30px;
    height: 30px;
    background-color: rgba(255, 26, 125, 0.3);
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
    animation: zoomSize3 2s infinite;
  }

  .block-about .list {
    @apply -mt-12 ml-auto mr-auto;

    max-width: 1000px;
  }

  .block-about .list .item {
    @apply flex flex-col align-middle justify-center p-16 text-center transition-all duration-300 tracking-wider;

    border: 1px solid #fff;
  }

  .block-about .list .item:hover {
    transform: translateY(-2rem);
    border-color: #ff1a7d;
  }

  .block-about .list .item span:first-child {
    @apply font-bold text-6xl;

    color: #ff1a7d;
  }

  .block-about .list .item span:last-child {
    @apply font-medium;
  }

</style>
