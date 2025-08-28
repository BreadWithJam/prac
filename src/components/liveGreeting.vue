<template>
<div>
    <h1>Welcome, {{ Username }}!</h1>
    <p>Input your name here:</p>
    <input type="text" placeholder="Name" v-model = "Cname"/>
</div>
</template>

<script>
import { ref } from 'vue'

export default{
  data(){
    const Cname = ref ('Jamyca')
    return { 
        Cname,
  }
},

computed:{
   Username(){
    return `${this.Cname}`
   }
}
}
</script>

<style>

</style>