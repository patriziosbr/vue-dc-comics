<template>
    <section>
         <div id='account-info'>
            {{ comic }}
        </div>
    </section>
</template>

<script>




export default {
    props: [
        'comic'
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
   }

</style>