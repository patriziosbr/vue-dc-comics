<template>

    <section>
         <div id='account-info'>
           <img :src="pippo.thumb" alt="">
           <p> {{ pippo.series }} </p>
        </div>
    </section>

</template>

<script>

export default {
    props: [
        'pippo'
    ]
    
}
</script>

<style lang="scss" scoped>

   section {
       
       width: calc(100% / 6 );
       padding: 24px;
       
   }

   #account-info {
      
       height: 200px;
       background-color: aquamarine;
       color: #fff;
       margin: 16px 0;

       img {
           width: 100%;
       }
       p {
           text-align: center;
           
       }
   }

</style>