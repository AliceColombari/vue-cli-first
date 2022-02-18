<template>
    <div class="jumbo-image">
        <div class="jumbo-text">
            <h1>Welcome to Australia</h1>
            <p>Get started on your vacation planning by exploring Australia via our 360° videos</p>
        </div>
    </div>
</template>


<script>
    export default {
  name: 'BonusHero'
}
</script>

<style scoped>
   .jumbo-image {
       max-width: 1200px;
       height: 650px;
       margin: auto;
       background-image: url('https://images6.alphacoders.com/926/926426.jpg');
       background-position: center;
       display: flex;
       justify-content: center;
       align-items: center;
   }

   .jumbo-text {
       margin: 80px;
       color: #fff;
       font-family: sans-serif;
       font-size: 20px;
       text-align: center;
   }

   .jumbo-text h1 {
       font-size: 100px;
       margin-bottom: 10px;
   }
</style>