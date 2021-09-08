<template>
    <div id="main-banner">
        <h1>Hamburgueria</h1>
    </div>
</template>

<script>
export default {
    name: 'Banner',
}
</script>

<style scoped>
#main-banner{
    background-image: url('/img/header2.jpg');
    background-size: contain;
    background-position: center;
    height: 621px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}
#main-banner h1{
    color: white;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
}
</style>