<template>
  <div class="header-wrapper">
    <div class="navbar-wrapper">
      <nav class="navbar">
        <div class="logo">
          <img class="logo-img" src="/logo.svg" height="64" alt="Nice green circle"/>
          eleague
        </div>
      </nav>
    </div>
    <div class="header-background">
      <div class="header-content">
        <div class="title">
          <div>eSports</div>
          <div>Tournaments</div>
        </div>
        <div class="subtitle">
          <div>for Universities in</div>
          <div>Mexico City</div>
        </div>
        <div class="button">
          Join the battle
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.header-wrapper {
  width: 100%;
  display: flex;
  height: 94vh;
  background-image:
    radial-gradient(
      #ACD5F7,
      #747AEB
    );
  align-items: center;
  flex-direction: column;
}
.navbar-wrapper {
  width: 1200px;
  display: flex;
  flex-direction: column;
  margin-bottom: 40px;
}
.navbar {
  width: 100%;
  display: flex;
  justify-content: space-between;
  padding: 10px 0;
}
.header-background {
  flex-grow: 1;
  background-image: url("/fortnite.png");
  background-repeat: no-repeat;
  background-position: right;
  background-size: contain;
  width: 100%;
  display: flex;
  justify-content: center;
}
.logo {
  display: flex;
  font-size: 32px;
  align-items: center;
  font-weight: 900;
  color: white;
}
.logo-img {
  height: 50px;
}
.header-content {
  width: 1200px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  padding: 0 50px;
}
.title {
  color: #04234e;
  font-size: 38px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  font-weight: 900;
  margin: -100px 0 10px 0;
}
.subtitle {
  color: white;
  font-size: 24px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin: 10px 0;
}
.button {
  background-color: #e8267d;
  color: white;
  padding: 10px 40px;
  text-transform: uppercase;
  font-weight: 900;
  margin-top: 100px;
  border-radius: 8px;
  box-shadow: 0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);
  cursor: pointer;
}
@media only screen and (max-width: 1250px) {
  .navbar-wrapper {
    width: 100%;
  }
}
@media only screen and (max-width: 900px) {
  .navbar-wrapper {
    width: 100%;
  }
  .header-background {
    background-size: cover;
    background-position: center;
  }
}
</style>
