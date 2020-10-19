<template>
  <section>
      <img :src="require('@/assets/'+picIconer+'')" alt="eat" id="eating" />
      <h2>{{ sectionTitle }}</h2>
      <p>{{ sectionText }}</p>
   
  </section>
</template>

<script>
export default {
    name:"ContentArea2",
    props: {
        sectionTitle:{
            type: String,
            default: ""
        }, 
        sectionText:{
            type: String,
            default: ""
        }, 
        picIconer:{
            type: String,
        }
           
    },
   
}
</script>

<style scooped>

    p {
        font-size: 30px;
        background-color: black;
        width: 700px;
        margin-left: 300px;
        border-radius: 20px;
    }

    h2{
        font-size: 35px;
    }
</style>