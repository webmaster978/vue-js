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
