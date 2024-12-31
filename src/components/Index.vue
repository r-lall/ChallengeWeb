<template>
  <div class="hello">
    <div id="app">
    <h1>Medieval Scroll</h1>
    <textarea v-model="message" placeholder="Petit cachotier..."></textarea>
    <br><br>
    <button @click="displayMessageRead">Générer une injure !</button>
    <br><br>
    <button @click="displayMessageCreate">Faites nous part de votre inspiration..</button>
    <br><br>
    <button @click="displayMessageUpdate">Quelque chose à changer ?</button>
    <br><br>
    <button @click="displayMessageDelete">Et puis quoi encore ?</button>
  
  </div>
    
  </div>
</template>

<script>
export default {
  name: 'IndexMain',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
textarea {
      width: 50%;
      height: 100px;
      border: 2px solid #6b4c35;
      border-radius: 5px;
      padding: 10px;
      font-size: 16px;
      resize: none;
    }
textarea:focus {
  outline: none;
  border-color: #a37d4f;
  box-shadow: 0 0 5px #a37d4f;
}
button {
      background: linear-gradient(90deg, #a38f4f, #d4b17f);
      border: none;
      color: rgb(255, 255, 255);
      font-size: 18px;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      transition: transform 0.2s, background 0.3s;
    }

button:hover {
  background: linear-gradient(90deg, #d4b17f, #a37d4f);
  transform: scale(1.05);
}
@keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
  

</style>
