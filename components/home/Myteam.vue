<template>
  <div class="block-team">
    <div class="container">
      <hgroup>
        <p>WHO WE ARE</p>
        <h2>MY TEAM</h2>
      </hgroup>

      <div class="list">
        <div class="item">
          <img src="../../static/images/taipham.jpg" alt="tải phạm">

          <div class="content">
            <h3>TAI PHAM</h3>
            <ul>
              <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
              <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
              <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
            </ul>
          </div>
        </div>

        <div class="item">
          <img src="../../static/images/uyendang.jpg" alt="uyển đặng">

          <div class="content">
            <h3>UYEN DANG</h3>
            <ul>
              <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
              <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
              <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
            </ul>
          </div>
        </div>

        <div class="item">
          <img src="../../static/images/vinhpham.jpg" alt="vinh phạm">

          <div class="content">
            <h3>VINH PHAM</h3>
            <ul>
              <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
              <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
              <li>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  .block-team {
    @apply bg-white text-black py-40;
  }

  .block-team .list {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 4rem;
    padding-top: 150px;
    max-width: 1000px;
    margin: 0 auto;
  }

  .block-team .item {
    flex: 0 0 auto;
  }

  .block-team .item img {
    @apply rounded-full;

    width: 100px;
    border: 1px solid #008aff;
    margin: -100px auto 3rem;
    box-shadow: 3px 0 20px 20px #1894fd2e;
  }

  .block-team .item h3 {
    padding: 2rem;
    background-color: #ff1a7d;
    text-align: center;
    color: #fff;
  }

  .block-team .item ul {
    padding: 3rem 0;
  }

  .block-team .item ul li {
    position: relative;
    letter-spacing: 1px;
    margin-bottom: 1rem;
  }

  .block-team .item ul li::before {
    content: "";
    display: inline-block;
    width: 10px;
    height: 2px;
    background-color: #222;
    margin-right: 15px;
  }

</style>
