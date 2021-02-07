<template>
  <div class="hello">
    <h1>Legends of Divine Justice</h1>
    <p>Quick find code: 320-321-201-65490980</p>
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
        <img :src="require('@/assets/img/rules_banner.png')" alt="">
      </div>
      <div class="text-left">
        <h3>Rules</h3>
        <p>Follow Jagex rules, being in our clan does not mean that the rules dont apply. Jagex rules are expected to be obeyed within our clan channel as well as on 
          forums. We strongly recommend using the "report abuse" button if jagex rules are broken by a clan member regardless of their rank. This includes inappropriate 
          language.</p>
        <router-link class="text-bold" to="/rules">read more</router-link>
      </div>

      <div>
        <img :src="require('@/assets/img/staff_banner.png')" alt="">
      </div>
      <div class="text-left">
        <h3>Clan Moderators</h3>
        <p>View our full list of Clan Moderators in LODJ.</p>
        <router-link to="/clan-mod" class="text-bold">read more</router-link>
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
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .container__hello::before, .container__hello::after {
    background: url('../assets/img/scroll-top.png') no-repeat center top;
    content: '';
    height: 50px;
    left: 0;
    position: absolute;
    width: 100%;
  }
  .container__hello::before {
    top: 180px;
  }

  .container__hello::after {
    top: 1060px;
  }

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
  right: 570px;
  position: absolute;
}

.pos-bot {
  position: absolute;
  right: 570px;
  top: 910px;
  padding-bottom: 20px;
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
