<template>
    <div id="nav">
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
        background: url('../assets/img/rsgroup.png') no-repeat center top;
        padding-top: 180px;
    }
    .title {
        text-align: center;
        font-size: 12.5px;
        border: 2px solid #382418;
        position: absolute;
        color: white;
        width: 40px;
        padding: 4px 50px;
        top: 40px;
        left: 0;
        right: 0;
        background: black;
        margin: 0 auto;

    }
</style>