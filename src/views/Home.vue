<template>
  <div class="home">
    <div class="home_banner-section"></div>

    <h1></h1>
  </div>

  <div class="btn btn-primary">123</div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
export default {
  name: "Home",
  components: {
    // HelloWorld,
  },
  mounted() {
    let loader = this.$loading.show({
      // Optional parameters
      container: this.fullPage ? null : this.$refs.formContainer,
      canCancel: true,
      onCancel: this.onCancel,
    });
    // simulate AJAX
    setTimeout(() => {
      loader.hide();
    }, 2000);
  },
};
</script>

<style lang="scss">
.home {
  max-width: 1280px;
  .home_banner-section {
    height: 100vh;
    width: 100vw;
    // padding-top: 114px;
    background-size: cover;
    background-position: 50%;
    background-attachment: fixed;
    background-image: url("https://picsum.photos/2000/2000");
  }
}
</style>