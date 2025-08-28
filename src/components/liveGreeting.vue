<template>
<div>
    <h1>Welcome, {{ Cname }}!</h1>
    <p>Input your name here:</p>
    <input type="text" placeholder="Name" v-model = "Cname"/>
</div>
</template>

<script>
import { ref } from 'vue'

export default{
    setup(){
        const Cname = ref('Jam')
    
    return{
        Cname,
         }
    }
}
</script>

<style>

</style>