<template>
<div class="conteur">
  {{ count }}

  <div class="conteur__button" @click="increment">+</div>
</div>
</template>
<script>

export default{
data (){
 return{
   count :0
  }
},
methods:{
  increment (){
  this.count++
  }
}
}
</script>

<style>
.conteur{
  font-weight : bold;
  width: 50px;
  height: 50px;
  background: rgb(35, 99, 173);
}
.conteur__button{
border: 1px solid #000 ;
}
</style>
