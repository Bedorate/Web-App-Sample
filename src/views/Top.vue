<template>
  <div class="top">
    <div class="top-title" @click="transHome">Web App Sample</div>
  </div>
</template>

<script>
export default {
  name: "Top",
  methods:{
    transHome(){
      this.$router.push('/home');
      //router-linkと動きは同じ htmlかjavascriptか
      //pushをreplaceに変えてみてね
    }
  }
};
</script>

<style lang="scss" scoped>
.top {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  //横のレイアウトを指定
  align-items: center;
  //縦のレイアウトを指定
  &-title {
    font-size: 36px;
  }
}
</style>