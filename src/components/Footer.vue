<template>
  <div class="footer-wrapper">
    <div class="footer">
      <div class="title">What are you waiting to show your skills?</div>
      <div class="email">contact@eleague.com</div>
      <div class="info">© 2018 eLeague Privacy Terms</div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .footer-wrapper {
    display: flex;
    width: 100%;
    justify-content: center;
  }
  .footer {
    width: 1200px;
    display: flex;
    flex-direction: column;
  }
  .title {
    font-size: 28px;
    font-weight: 900;
    margin: 60px 0 20px 0;
  }
  .info {
    width: 100%;
    display: flex;
    justify-content: flex-start;
    padding: 24px 0;
  }
@media only screen and (max-width: 1250px) {
  .footer {
    width: 100%;
    padding: 0 20px;
  }
}
@media only screen and (max-width: 450px) {
  .title {
    margin-bottom: 40px;
  }
  .info {
    margin-top: 40px;
  }
}
</style>
