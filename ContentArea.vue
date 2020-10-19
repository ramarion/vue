<template>
  <section>
      
      <img :src="require('@/assets/'+picIconed+'')" alt="game" id="gaming" /> 
      <h2>{{ sectionTitle }}</h2>
      <p>{{ sectionText }}</p>
   
  </section>
</template>

<script>
export default {
    name:"ContentArea",
    props: {
        sectionTitle:{
            type: String,
            default: ""
        }, 
        sectionText:{
            type: String,
            default: ""
        }, 
        picIconed:{
            type: String,
        }   
           
    },
   
}
</script>

<style>

</style>