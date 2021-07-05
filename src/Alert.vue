<template>
<div>
  <div class="ul message success" v-if="visible">
   Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugiat aliquid iste voluptates incidunt expedita perferendis officiis! Minus itaque dicta placeat tempore voluptas, repudiandae magnam omnis quas delectus, porro, aspernatur quaerat.
</div>
<button @click="toggle">Toggle</button>
</div>
</template>
<script>
export default {
  data () {
return{
 visible: false
}
  },
  methods : {
    toggle: function (){
this.visible = this.visible
    }

  }
}
</script>
