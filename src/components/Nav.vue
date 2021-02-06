<template>
    <div id="nav">
        <img :src="require('@/assets/img/rsgroup.png')" alt="logo">
        <div class="title"> LODJ </div>
    </div>
</template>

<style scoped>
    #nav {
        position: relative;
    }
    .title {
        border: 2px solid #382418;
        font-weight: bold;
        position: absolute;
        color: white;
        padding: 10px 50px;
        top: 65px;
        left: 880px;
        background: black;
    }
</style>