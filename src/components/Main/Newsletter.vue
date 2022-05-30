<template>
  <div>
    <div id="newsletter" class="d-flex justify-content-center align-items-center flex-column text-center">
      <div>
        <h4>Subscribe to our Newsletter</h4>
      </div>
      <div class="text-center">
        <input id="testo" type="text" placeholder="Inserisci la tua mail">
        <input id="invia" type="Submit">
      </div>
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'NewsLetterVue',
}
</script>

<style lang="scss" scoped>

#newsletter{
  height: 300px;
  padding: 40px;
  background-color: #F2F2F2;
}

h4{
  font-size: 30px;
  margin-bottom: 30px;
  font-weight: 700;
}

#testo{
  width: 500px;
  margin-right: 10px;
  padding: 5px;
}

#invia{
  padding:5px;
  background-color: black;
  font-size: 15px;
  text-decoration: none;
  color: white;
  font-weight: 700;
  width: 250px;
  text-transform: uppercase;
  &:hover{
    background-color: #27AABE;
    animation-duration: 0.6s;
    transition-timing-function: ease;
    border: 1px solid #27AABE;
  }
}

</style>