<template>
  <div class="tournament-wrapper">
    <img class="image" :src="image">
    <div class="title">
      {{ title }}
    </div>
    <div class="date">
      {{ date }}
    </div>
    <div class="location">
      {{ location }}
    </div>
    <div class="button">
      Sign up
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    date: String,
    image: String,
    location: String,
  },
};
</script>

<style lang="scss" scoped>
  .image {
    min-width: 100%;
    max-width: 100%;
    height: auto;
    border-radius: 20px;
    margin-bottom: 10px;
    box-shadow: 0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);
  }
  .title {
    font-weight: 900;
    margin: 10px 2px;
    font-size: 18px;
    text-align: start;
  }
  .date {
    margin: 10px 2px;
    text-align: start;
  }
  .location {
    margin: 10px 2px;
    text-align: start;
  }
  .button {
    font-weight: 900;
    margin: 20px 2px;
    font-size: 16px;
    text-align: start;
    display: flex;
    justify-content: center;
    width: 45%;
    padding: 10px;
    background-color: #e8267d;
    border-radius: 8px;
    color: white;
    box-shadow: 0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);
    cursor: pointer;
  }
</style>
