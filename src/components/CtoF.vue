
<template>
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"></link>

 <div>
    <h2> Celsius to fahrenheit converter</h2>
 </div>
<div class = "row">
    <div class = "col-lg-5">
        <div>
            <p>Input the celsius value here:</p>
            <input type="text" placeholder="Celsius">

            <div>
                <button style="margin-top: 40px;">Submit</button>
            </div>
        </div>
    </div>
    <div class = "col-lg-2">
        <i class="fa-solid fa-arrow-right" style="margin-left: 40px; margin-top: 21px;"></i>

        <div style="margin-top:80px;">
            <p>Result:</p>
            <input type="text">
        </div>
    </div>

    <div class="col-lg-5" style="margin-left: 65px;">
        <p>Input the fahrenheit value here:</p>
        <input type="text" placeholder="Fahrenheit">
    </div>
</div>


</template>

<script>

</script>

<style>
.first{
margin:0;
padding: 5px;
}

input [type='text']{
    margin-top:10px;
    
}
.row{
    display: flex;
}
</style>