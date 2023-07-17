<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>
  
<script>
  
  export default {
    name: 'Banner',
    components: {
      
    }
  }
</script>
<style scoped>
  #main-banner {
    background-image: url('/public/img/th.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: flex-start;

  }

  #main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 50px;
    background-color: #222;
    padding: 20px 40px;
  }
</style>