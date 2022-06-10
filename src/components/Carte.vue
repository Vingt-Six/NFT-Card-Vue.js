<template>
    <div class="carte">
        <div class="image">
            <img src="@/assets/img/image-equilibrium.jpg" alt="" />
        </div>
        <div class="text">
            <h3>Equilibrium #3429</h3>
            <p>Our Equilibrium collection promotes balance and calm.</p>
            <div class="ethclock">
                <div class="ether">
                    <img src="@/assets/img/icon-ethereum.svg" alt="ether" />
                    <p>0.041ETH</p>
                </div>
                <div class="clock">
                    <img src="@/assets/img/icon-clock.svg" alt="clock" />
                    <p>3 days left</p>
                </div>
            </div>
            <hr>
            <div class="avatar">
                <img src="@/assets/img/image-avatar.png" alt="">
                <p>Creation of <span>Jules Wyvern</span></p>
            </div>
        </div>
    </div>
</template>

<style scoped lang="sass">
.carte
    width: 22vw
    overflow: hidden
    background-color: hsl(216, 50%, 16%)
    border-radius: 10px
    .image
        width: 19vw
        margin-inline: auto
        margin-top: 19px
        border-radius: 10px
        img
            width: 100%
            border-radius: 10px
    .text
        margin-inline: 1.5vw 
        h3
            color: white
        h3:hover
            color: hsl(178, 100%, 50%)
            cursor: pointer
        p
            color: hsl(215, 51%, 70%)
            font-weight: 100
        .ethclock
            display: flex
            justify-content: space-between
            .ether
                display: flex
                align-items: center
                p
                    color: hsl(178, 100%, 50%)
                    margin-left: 6px
                    font-size: 13px
            .clock
                display: flex
                align-items: center
                p
                    color: hsl(215, 51%, 70%)
                    margin-left: 6px
                    font-size: 13px
        hr
            height: 0.8px
            background-color: rgba(200, 200, 200, 0.3)
            border: none
        .avatar
            display: flex
            align-items: center
            margin-bottom: 20px
            img
                width: 11%
                border: white 1px solid
                border-radius: 50%
            p
                font-size: 14px
                margin-left: 20px
                span
                    color: white
                span:hover
                    color: hsl(178, 100%, 50%)
                    cursor: pointer
</style>
