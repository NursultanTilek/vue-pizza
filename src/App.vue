<template>
  <div class="wrapper">
    <router-view />
  </div>

</template>


<script>
import Header from "@/components/Header.vue";
export default {
  components: { Header }

}
</script>
<style>
@import url(./assets/css/app.css);

</style>
