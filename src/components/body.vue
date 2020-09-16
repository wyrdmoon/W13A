<template>
   <div>
      <div></div> 
      <h3>BODY FIRST</h3>
      <h3>BODY SECOND</h3>
      <h3>BODY THIRD</h3>
       
       </div> 
</template>


<script>
export default {
    name: "page-body"
}
</script>

<style lang="stylus" scoped>

</style>
<style scoped>
.page-body {
    display: grid;
    justify-items: center;
    align-items: center;
    grid-template-columns: 25% 25% 25% 25%;
    width: 100%;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    
}

