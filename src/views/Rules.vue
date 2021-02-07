<template>
    <div id="rules">
        <h1>Rules and Disclamers</h1>

       <div class="container__rules">
            <div class="container">
                <p>1. Follow jagex rules, being in our clan does not mean that the rules dont apply. Jagex rules are expected to be obeyed within our clan channel as 
                    well as on forums. We strongly recommend using the "report abuse" button if jagex rules are broken by a clan member regardless of their rank. 
                    This includes inappropriate language.</p>

                <p>
                    2. Respect Your clan members, regardless of their rank, please do not bring drama into the clan or attempt to disrupt members.  
                </p>

                <p>
                    3. Respect higher ranks kick/ban ability. If someone is removed from the clan channel please ask one of the generals/leaders why in private
                     chat and not instigate trouble in the clan channel.
                </p>

                <p>
                    4. No Multi-Clanning or advertising other clans (exceptions are being made to pvm/minigame clans in osrs)
                </p>

                <p>
                    5. No repeated buying/selling or lending in clan-chat. (this includes rank begging/hinting for promotions, you will be promoted of the higher 
                    ranks vote on it)
                </p>

                <p>
                    6. No discrimination: This includes, but not limited to race, gender, religion, martial status, mental/physical abilities, likes, dislikes, 
                    etc.. The reason we have this rule is any dispute over the above issues will cause arguments.
                </p>

                <p>
                    7. Offensive names are not tolerated in LODJ. If you change your name to something offensive you will be *instantly* banned from clan.
                </p>

                <p>
                    8. In your application add your favorite color beside "have you read the rules".
                </p>

                <p>
                    9. No giving or sharing account/personal details in clan-chat.
                </p>

                <p>
                    10. You will be warned before receiving a kick unless its a serious matter.
                </p>

                <p>
                    11. Have fun after all this is the most important rule.
                </p>

                <p>
                    12. No use of macro scripts or botting, this also is against jagex rules and you will be removed on the spot from our clan if caught.
                </p>
            </div>
       </div>
    </div>
</template>

<style scoped>
.container {
    padding: 0 80px;
}
.container__rules {
    padding: 0 25px;
    margin: 0 auto;
    width: 745px;
    height: 10px;
}

p {
    text-align: left;
    padding-top: 10px;
}
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

#rules {
    padding-top: 20px;
    padding-bottom: 100px;
    height: 600px;
    background: url('../assets/img/scroll-base.png') repeat-y top center;
}

#rules::before, #rules::after {
    background: url('../assets/img/scroll-top.png') no-repeat center top;
    content: '';
    height: 50px;
    left: 0;
    position: absolute;
    width: 100%;
}

#rules::before {
    top: 180px;
}

#rules::after {
    top: 900px;
}
</style>