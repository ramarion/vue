<template>
  <section>
      <img :src="require('@/assets/'+picIcon+'')" alt="slept" id="sleeping" />
      <h2>{{ sectionTitle }}</h2>
      <p>{{ sectionText }}</p>
   
  </section>
</template>

<script>
export default {
    name:"ContentArea1",
    props: {
        sectionTitle:{
            type: String,
            default: ""
        }, 
        sectionText:{
            type: String,
            default: ""
        }, 
        picIcon:{
            type: String,
        }
           
    },
   
}
</script>

<style>

</style>