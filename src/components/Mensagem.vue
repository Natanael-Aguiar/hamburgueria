<template>
    <div class="mensagem-container">
        <p>{{msg}}</p>
    </div>
</template>

<script>
export default {
    name:'Mensagem',
    props:{
        msg:String,
    }    
}
</script>

<style scoped>
    .mensagem-container{
        color: #004085;
        background-color: #cce5ff;
        border: 2px solid #b8daff;
        border-radius: 5px;
        padding: 10px;
        width: 400px;
        margin: 30px auto;
    }
</style>