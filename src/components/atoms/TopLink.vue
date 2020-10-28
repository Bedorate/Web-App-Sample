<template>
  <div class="top-link" @click="transTop">トップに戻る</div>
</template>

<script>
export default {
  name: "TopLink",
  methods:{
    transTop(){
      this.$router.push("/")
    }
  }
}
</script>

<style lang="scss" scoped>
.top-link{
 color:white;
 font-size: 12px;
}
</style>