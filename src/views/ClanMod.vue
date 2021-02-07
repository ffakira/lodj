<template>
    <div id="clan-list">
        <h1>Clan Moderators</h1>

        <div class="container__clan-list">
            <p :key="index" v-for="(general, index) in generals">
                <img :src="require('@/assets/img/rank/general.png')" alt="general.png">
                {{general}}
            </p>

            <p :key="index" v-for="(captain, index) in captains">
                <img :src="require('@/assets/img/rank/captain.png')" alt="captain.png">{{captain}}
            </p>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            generals: [
                'Cillian/Paddle Time - Retired Admin',
                'Clan List - Admin',
                'Daf - Admin',
                'Denieru/Estrogen - Retired Admin',
                'Hardman/Hardie - Elder',
                'Fauroi',
                'Zhen Ji - Elder',
                'Bubblies',
                'Longord5/Longord2',
                'Kronopes',
                'No pk',
                'Asyla - Recruitment team member'
            ],
            captains: [
                'Myster wong',
                'Qrow',
                'HeavyDuty',
                'Bubbles',
                'Tigoko',
                'Cooj',
                'Dragon Fan'
            ]
        }
    }
}
</script>

<style scoped>
p, a {
    text-decoration: none;
    font-size: 11.5px;
}

h1 {
    padding-top: 2rem;
    text-align: center;
    color: #6D4211;
    font-size: 2.0em;
    font-weight: bold;
    text-shadow: 1px 1px 1px #000000;
}

#clan-list {
    padding-top: 20px;
    padding-bottom: 100px;
    min-height: 200px;
    background: url('../assets/img/scroll-base.png') repeat-y top center;
}

#clan-list::before, #clan-list::after {
    background: url('../assets/img/scroll-top.png') no-repeat center top;
    content: '';
    height: 50px;
    left: 0;
    position: absolute;
    width: 100%;
}

#clan-list::before {
    top: 180px;
}

#clan-list::after {
    top: 1000px;
}
</style>