<template>
    <div class="hero">
        <div class="hero-info">
            <div class="hero-info__text">
                <h2 class="hero-info__title">Luxury homeware for people who love timeless design quality</h2>
                <span class="hero-info__description">Shop the new Spring 2022 collection today</span>
            </div>  
            <a class="hero-info__link" href="#">View collection</a>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.hero{
    background-image: url(/img/hero.png);
    height: 704px;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: end;
    padding-right: 80px;
    &-info{
        background: #fff;
        max-width: 630px;
        padding: 50px 55px;
        height: 444px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: flex-start;
        &__title{
            font-family: 'Clash Display', sans-serif;
            font-style: normal;
            font-weight: 400;
            font-size: 32px;
            line-height: 140%;
            margin: 0 0 20px 0;
        }
        &__description{
            font-family: 'Satoshi', sans-serif;
            font-style: normal;
            font-weight: 400;
            font-size: 18px;
            line-height: 150%;
        }
        &__link{
            display: inline-block;
            padding: 16px 32px;
            background: #F9F9F9;
            color: #2A254B;
            text-decoration: none;
            &:hover{
                background: #f0f0f0;
                text-decoration: underline;
            }
        }
    }
}
</style>