<template>
    <div class="header-grid">
        <img alt="Vue logo" src="../assets/logo.png">
        <div></div>
        
        <h3>HEADER FIRST</h3>
        <h3>HEADER SECOND</h3>
        <h3>HEADER THIRD</h3>
    </div>
</template>

<script>
export default {
    name: "page-header"
}

</script>

<style scoped>
  .header-grid {
      display: grid;
      justify-items: center;
      align-items: center;
      grid-template-columns: 1fr 2fr 1fr 1fr 1fr;
      }

</style>