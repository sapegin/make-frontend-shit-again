<template>
  <section class="container">
    <div>
      <img 
        class="logo" 
        src="../assets/dope.gif" 
        alt="Geocities was dope">
    </div>
    <img 
      class="image1" 
      alt="debugging the mind" 
      src="../assets/debuggingthemind.gif">
    <img 
      class="image2" 
      alt="Computer from the 80s with rainbow glowing screen" 
      src="../assets/frontend1.gif">
    <img 
      class="image3" 
      alt="a planet with pizza and hearts on top" 
      src="../assets/pizzalove.gif">
    <img 
      class="image4" 
      alt="seal with earth spinning on its nose" 
      src="../assets/dolphin.gif">
    <img 
      class="image5" 
      alt="" 
      src="../assets/dolphin.gif">
  </section>
</template>

<style scoped>
.container {
  background: url("../assets/bg4.png");
}

img {
  position: absolute;
}

.image3 {
  right: 0;
  top: 0;
}

.image2 {
  left: 0;
  top: 0;
}

.image4 {
  left: 0;
  bottom: 0;
}

.image5 {
  right: 0;
  bottom: 0;
  transform: scaleX(-1);
}

.logo {
  position: relative;
  z-index: 10;
}
</style>
