<template>
    <div id="nav">
        <img :src="require('@/assets/img/rsgroup.png')" alt="logo">
        <div class="title"> 
            <p>LODJ</p>
            <router-link to="/">Home</router-link>
        </div>
    </div>
</template>

<style scoped>
    p {
        padding: 0;
        margin: 0;
        font-weight: bold;
        margin-bottom: 4px;
    }
    a {
        color: #90c040 !important;
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }
    #nav {
        position: relative;
    }
    .title {
        font-size: 12.5px;
        border: 2px solid #382418;
        position: absolute;
        color: white;
        padding: 4px 50px;
        top: 65px;
        left: 880px;
        background: black;
    }
</style>