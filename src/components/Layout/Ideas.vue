<template>
    <div class="ideas">
        <div class="ideas-info">
            <div class="ideas-info__text">
                <h2 class="ideas-info__title">It started with a small idea</h2>
                <span class="ideas-info__description">A global brand with local beginnings, our story begain in a small studio in South London in early 2014</span>
            </div>  
            <a class="ideas-info__link" href="#">View collection</a>
        </div>
        <div class="ideas-img">
            <img class="ideas__img" src="/img/room.jpg" alt="">
        </div>
    </div>
</template>


<style lang="scss" scoped>
.ideas{
    display: flex;
    justify-content: space-between;
    padding:0 80px;
    margin-top: 100px;
    &-info{
        background: #2A254B;
        max-width: 630px;
        padding: 50px 55px;
        height: 478px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: flex-start;
        &__title{
            font-family: 'Clash Display';
            font-style: normal;
            font-weight: 400;
            font-size: 32px;
            line-height: 39px;
            color: #FFFFFF;
            margin: 0 0 20px 0;
        }
        &__description{
            font-family: 'Satoshi';
            font-style: normal;
            font-weight: 400;
            font-size: 18px;
            line-height: 24px;
            color: #FFFFFF;
        }
        &__link{
            display: inline-block;
            padding: 16px 32px;
            background: rgba(249, 249, 249, 0.15);
            color: #fff;
            text-decoration: none;
            &:hover{
                background: rgba(249, 249, 249, 0.288);
                text-decoration: underline;
            }
        }
    }
}
</style>