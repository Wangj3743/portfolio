<script>

</script>


<template>
  <!-- title --> 
  <div class="bg-img bg-cover bg-center h-screen w-full flex items-center justify-center"> <!--bg image+blur-->
    <div class="blur-rectangle backdrop-blur-md absolute h-screen w-full"></div>
  </div>
  <div class="text-center absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2"> <!--text-->
    <span class="text-[40px] text-white">Jim Wang's
      <div class="text-[120px] font-bold">Portfolio</div>
    </span>
  </div>

  <!-- content -->
  <div class="relative  m-auto w-[70%] text-center">
    <br><br><br>
    <h1 class="text-[30px] font-bold">Graphic Designs</h1><br>
      <div class="grid grid-cols-2 gap-4">
        <img src="/images/graphic/landscape1.png" alt="landscape 1">
        <img src="/images/graphic/landscape2.png" alt="landscape 2">
      </div>
      <div class="grid grid-cols-3 gap-4">
        <img src="/images/graphic/poster1.png" alt="poster 1">
        <img src="/images/graphic/poster3.png" alt="poster 3">
        <img src="/images/graphic/poster2.png" alt="poster 2">
        <img src="/images/graphic/square1.png" alt="square 2">
        <img src="/images/graphic/square2.png" alt="square 3">
        <img src="/images/graphic/square3.png" alt="square 4">
      </div><br><br><br>
    <h1 class="text-[30px] font-bold">3D models</h1><br>
      <div class="grid grid-cols-3 gap-4">
        <img src="/images/cad/1.png" alt="CAD 1">
        <img src="/images/cad/3.png" alt="CAD 3">
        <img src="/images/cad/4.png" alt="CAD 4">
        <div></div>
        <img src="/images/cad/2.png" alt="CAD 2">
      </div><br><br><br>
    <h1 class="text-[30px] font-bold">Instagram</h1><br>
      <div class="grid grid-cols-3 gap-4">
        <div><img src="/images/insta/jim.png" alt="insta 1"><a href="https://www.instagram.com/_jimwang/" target="blank">Personal Account</a></div>
        <div><img src="/images/insta/jam.png" alt="insta 2"><a href="https://www.instagram.com/jamhacks/" target="blank">JAMHacks</a></div>
        <div><img src="/images/insta/rythm1.png" alt="insta 3"><a href="https://www.instagram.com/rythm.hacks/" target="blank">RythmHacks (new style)</a></div>
        <div><img src="/images/insta/rythm2.png" alt="insta 4"><a href="https://www.instagram.com/rythm.hacks/" target="blank">RythmHacks (old style)</a></div>
        <div><img src="/images/insta/cubing.png" alt="insta 5"><a href="https://www.instagram.com/lhss.cubing.club/" target="blank">Laurel Heights' Cubing Club</a></div>
        <div><img src="/images/insta/clock.png" alt="insta 6"><a href="https://www.instagram.com/clockhacks/" target="blank">ClockHacks</a></div>
        <div><img src="/images/insta/design.png" alt="insta 7"><a href="https://www.instagram.com/lhss.design.club/" target="blank">Laurel Heights' Design Club</a></div>
      </div><br><br><br>
  </div>

  <!-- footer -->
  <div class="bg flex flex-row gap-2 justify-center">
    <a class="hover:scale-[1.2] ease-in duration-200" href="mailto:jimwang314@gmail.com">
      <img class="iconSize" src="/src/assets/profiles/envelope.svg" />
    </a>
    <a class="hover:scale-[1.2] ease-in duration-200" href="https://www.linkedin.com/in/jim-wang-263877212/">
      <img class="iconSize" src="/src/assets/profiles/linkedin.svg" />
    </a>
    <a class="hover:scale-[1.2] ease-in duration-200" href="https://github.com/Wangj3743/">
      <img class="iconSize" src="/src/assets/profiles/github.svg" />
    </a>
  </div>
  <br>
  <div class="text-center">
    <!-- <a href="legacy\legacy.html">legacy</a> -->
  </div>
  <br>
  
</template>


<style>
  /* html, body {
    height: 100%;
  } */
  template, body, .bg {
    @apply bg-white dark:bg-[#1e2124];
  }

  h1, h2, h3, p, li, details, summary {
    @apply text-black dark:text-white fill-black;
  }

  a {
    @apply text-[#0015ff] dark:text-[paleturquoise]
  }

  .iconSize {
    height: 32px;
    width: 32px;
  }

  .bg-img {
  background-image: url('/images/8O0A3799.JPG');
  }
</style>