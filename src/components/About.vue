<template>
  <div class="about-us-wrapper">
    <div class="about-us">
      We are a group of passionate gamers that seek to share this
      through massive gaming events in Mexico City
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .about-us-wrapper {
    width: 100%;
    display: flex;
    height: 180px;
    background-image: url("/about.jpg");
    background-repeat: no-repeat;
    background-position: right;
    background-size: cover;
    align-items: center;
    justify-content: center;
    filter: sepia(.3);
  }
  .about-us {
    color: white;
    width: 1200px;
    padding: 0 50px;
    font-size: 24px;
    text-align: start;
    line-height: 30px;
  }
@media only screen and (max-width: 450px) {
  .about-us-wrapper {
    height: 300px;
  }
}
</style>
