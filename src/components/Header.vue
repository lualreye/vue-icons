<script setup>
import Icons from '../components/Icons.vue'

</script>

<template>
  <header class="header">
    <img src="../assets/logo.png" alt="logo" class="logo">
    <div class="icons-section">
      <div class="icon-wrapper">
        <Icons name="facebook" />
      </div>
    </div>
  </header>
</template>

<style scoped>
.header {
  width: 100%;
  max-width: 1280px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0;
  margin: 0 auto;
}
.logo {
  width: 45px;
  height: 45px;
}
.icon-wrapper {
  width: 32px;
  height: 32px;
  color: #3b5998;
}
</style>