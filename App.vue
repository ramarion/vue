<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/header.png">
    <Title  subTitle="Here is a list of things I did this summer."></Title>
    <ContentArea2 picIconer="eat.jpg" sectionTitle="Eat" sectionText="Ate all my favourite meals and desserts"></ContentArea2>
     <ContentArea1 picIcon="sleep.jpg" sectionTitle="Sleep" sectionText="Slept during the day and night!"></ContentArea1>
      <ContentArea picIconed="game.png" sectionTitle="Play" sectionText="Played video games everyday!"></ContentArea>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import ContentArea from './components/ContentArea.vue'
import ContentArea1 from './components/ContentArea1.vue'
import ContentArea2 from './components/ContentArea2.vue'

export default {
  name: 'App',
  components: {
    Title,
    ContentArea,
    ContentArea1,
    ContentArea2
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-bottom: 60px;
  background-image: url(./assets/573249.jpg);
  background-repeat: no-repeat;
  color: aliceblue;
  
}

img{
  border-radius: 200px;
  width: 15.5em;
  height: auto;
}

body{
  background-color: black;
}
</style>
