<template>
  <div class="global-header">
    <div>
      <header-logo />
    </div>
    <div>
      <top-link />
    </div>
  </div>
</template>

<script>
import HeaderLogo from "@/components/atoms/HeaderLogo.vue"
import TopLink from "@/components/atoms/TopLink.vue"

export default {
  name: "HeaderHeader",
  components:{
    HeaderLogo,
    TopLink,
  }
}
</script>

<style lang="scss" scoped>
.global-header{
  position:fixed;
  width: 100%;
  height: 72px;
  background: black;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0px 16px;
}
</style>