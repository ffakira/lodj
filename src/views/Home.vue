<template>
  <div id="home">
    <h1>Legends of Divine Justice</h1>
    <p class="mb-3">Quick find code: 320-321-201-65490980</p>
    <div class="container__home">
      <div class="container">
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
      </div>

      <div class="container">
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
      </div>

      <div class="container">
        <div>
          <img :src="require('@/assets/img/staff_banner.png')" alt="">
        </div>
        <div class="text-left">
          <h3>Clan Moderators</h3>
          <p>View our full list of Clan Moderators in LODJ.</p>
          <router-link to="/clan-mod" class="text-bold">read more</router-link>
        </div>
      </div>

      <div class="container">
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
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.mb-3 {
  margin-bottom: 3rem;
}
#home {
  padding-top: 20px;
  padding-bottom: 100px;
  height: 780px;
  background: url('../assets/img/scroll-base.png') repeat-y top center;
}
  
#home::before, #home::after {
  background: url('../assets/img/scroll-top.png') no-repeat center top;
  content: '';
  height: 50px;
  left: 0;
  position: absolute;
  width: 100%;
}
  
#home::before {
  top: 180px;
}

#home::after {
  top: 1080px;
}

.container {
  padding: 0 80px;
  display: grid;
  grid-template-columns: 40% 60%;
  margin: 0 auto;
  min-height: 150px;
}

.container__home {
  padding: 0 25px;
  margin: 0 auto;
  width: 745px;
  height: 10px;
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
