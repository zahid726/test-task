<template>
  <div class="heading">
    <h1>Welcome to Your <br> Virtual Office.</h1>
  </div>
  <div class="row">
    <div class="col">
      <div class="container">
        <div class="inner">
          <div class="icon">
             <span class="iconify" data-icon="mdi:account-cancel"></span>
          </div>
        </div>
      </div>
     <a href=""> <h3>verify crendentials</h3></a>
    </div>
    <!--  -->
      <div class="col">
      <div class="container">
        <div class="inner">
          <div class="icon">
          <span class="iconify" data-icon="mdi:human"></span>


          </div>
        </div>
         
      </div>
     <a href=""> <h3>Lunch Consultaton</h3></a>
    </div>
    <!--  -->
      <div class="col">
      <div class="container">
        <div class="inner">
          <div class="icon">
            <span class="iconify" data-icon="mdi:star-david"></span>

          </div>
        </div>
      </div>
    <a href=""> <h3>Open new link</h3></a>
    </div>
     
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
font-size: 2.2rem;
}

.row{
  width: 100%;
  display: flex;
  justify-content: center;
  text-align: center;
  align-items: center;
  align-content: center;
}
.row .col{
  width: 28%;
  margin: 0% auto; 
}
.col .container{
  height: 150px;
  width: 150px;
  text-align: center;
  background-color: #7ac4c1;
  border-radius: 50%;
  border: 1px solid black;
  display: flex;
  align-content: center;
  align-items: center;
  justify-content: center;
  margin: 0 auto;
}
.col .container .inner{
  height: 70px;
  width: 70px;
  background-color: black;
  border-radius: 50%;
}
.icon{
  color: white;
  display: flex;
  font-size: 45px;
  height: 65px;
  justify-content: center;
flex-direction:center;
  align-items: center;
  border: 4px solid white;
  border-radius: 50%;
}
h3{
  font-family: 'Rampart One', cursive;
  font-size: 1.3rem;
  color: #dac671;
}
a{
  text-decoration: none;
}
</style>
