<template>
  <div class="tournaments-wrapper">
    <div class="tournaments">
      <div class="title">Tournaments</div>
      <div class="tournaments-list">
        <div class="tournament">
          <Tournament
            title="Fortnite"
            image="/tournaments/Fortnite.png"
            location="Universidad Panamericana"
            date="21 - 23 Nov"
          >
          </Tournament>
        </div>
        <div class="tournament">
          <Tournament
            title="FIFA 19"
            image="/tournaments/Fifa 19.png"
            location="Universidad Panamericana"
            date="12 - 17 Dic"
          >
          </Tournament>
        </div>
        <div class="tournament">
          <Tournament
            title="Madden 19"
            image="/tournaments/Madden 19.png"
            location="Universidad Panamericana"
            date="14 - 20 Dic"
          >
          </Tournament>
        </div>
        <div class="tournament">
          <Tournament
            title="COD: Black Ops IV"
            image="/tournaments/COD.png"
            location="Universidad Panamericana"
            date="04 - 09 Ene"
          >
          </Tournament>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Tournament from '@/components/Tournament.vue';

export default {
  components: {
    Tournament,
  },
};
</script>

<style lang="scss" scoped>
  .tournaments-wrapper {
    background-color: #f0f9f8;
    width: 100%;
    min-height: 300px;
    display: flex;
    justify-content: center;
  }
  .tournaments {
    width: 1100px;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 60px 50px;
  }
  .title {
    font-weight: 900;
    font-size: 24px;
  }
  .tournaments-list {
    width: 100%;
    display: flex;
    justify-content: space-between;
    margin-top: 60px;
  }
  .tournament {
    max-width: 200px;
  }
@media only screen and (max-width: 1250px) {
  .tournaments-list {
    flex-wrap: wrap;
  }
  .tournament {
    max-width: 30%;
    margin-bottom: 28px;
  }
}
@media only screen and (max-width: 750px) {
  .tournament {
    max-width: 45%;
  }
}
@media only screen and (max-width: 450px) {
  .tournament {
    max-width: 98%;
  }
}
</style>
