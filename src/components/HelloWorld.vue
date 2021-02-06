<template>
  <div class="hello">
    <img class="pos-top" alt="Vue logo" :src="require('@/assets/img/scroll-top.png')">
    <h1>Legends of Divine Justice</h1>
    <div class="container__hello pt-2">

      <div>
      <a href="https://secure.runescape.com/m=forum/forums?320,321,201,65490980" target="_blank">
        <img :src="require('@/assets/img/intro_banner.png')" alt="intro_banner">
      </a>
      </div>
      <div class="text-left">
        <h3>Introduction</h3>
        <p>Welcome to the Legends Of Divine Justice (L O D J); old school Runescape recruitment thread. We are a mature social and community based clan, which is well 
          established with roots dating back to RSC. We welcome anyone interested in joining our friendly and knowledgeable family.</p>
        <a href="https://secure.runescape.com/m=forum/forums?320,321,201,65490980" target="_blank" class="text-bold">read more</a>
      </div>

      <div>
        <a href="https://discord.gg/AUMryRZkgS" target="_blank">
          <img :src="require('@/assets/img/discord_banner.png')" alt="discord_banner">
        </a>
      </div>
      <div class="text-left">
        <h3>LODJ On Discord</h3>
        <p>Want to be part of LODJ discord family? Just visit our Friend Chat, and ask one of our rank members to invite you to our Discord.</p>
      </div>

    </div>
    <img class="pos-bot" alt="Vue logo" :src="require('@/assets/img/scroll-top.png')">
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  padding-bottom: 100px;
}

.text-left {
  text-align: left;
}

a {
  padding: 0;
  margin: 0;
}

p, a {
  text-decoration: none;
  font-size: 11.5px;
}

.text-bold {
  font-weight: bold;
  color: #6D4211;
}

.container__hello {
  display: grid;
  grid-template-columns: 40% 60%;
  margin: 0 700px;
  row-gap: 3em;
}
h3 {
  color: #6D4211;
  margin: 0 !important;
  padding: 0;
}

h1 {
  padding-top: 20px;
  text-align: center;
  color: #6D4211;
  font-size: 2.0em;
  font-weight: bold;
  text-shadow: 1px 1px 1px #000000;
}

.pt-2 {
  padding-top: 2rem;
}

.pos-top {
  top: 180px;
  right: 576px;
  position: absolute;
}

.pos-bot {
  position: absolute;
  right: 576px;
  top: 680px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
