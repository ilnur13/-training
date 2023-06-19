<template>
    <div class="products4Column-elements">
        <div class="products4Column-element"
        v-for="(element, i) of products4Column"
        :key="i">
            <a class="products4Column__prod" href="#">
                <img
                :src="element.img"
                alt="element.title"
                class="products4Column-element__img">
                <h4 class="products4Column-element__title">{{element.title}}</h4>
                <span class="products4Column-element__price">{{ element.price }}</span>
            </a>
        </div>
    </div>
    <div class="products4Column__links">
        <a class="products4Column__link" href="#">View collection</a>
    </div>
</template>

<script setup>
import {ref} from 'vue'

const products4Column = [
 {
    img:'/img/product1.jpg',
    title: 'The Dandy chair',
    price: '£250'
 },
 {
    img:'/img/product2.jpg',
    title: 'Rustic Vase Set',
    price: '£155'
 },
 {
    img:'/img/product3.jpg',
    title: 'The Silky Vase',
    price: '£125'
 },
 {
    img:'/img/product4.jpg',
    title: 'The Lucy Lamp',
    price: '£399'
 },
]
</script>

<style lang="scss" scoped>
.products4Column {
    padding: 80px 80px 10px 0;
    &__prod{
        display: block;
        text-decoration: none;
        &:hover{
            text-decoration: underline;
            color: #2A254B;
            opacity: 0.9;
        }
        &__title{
        font-family: 'Clash Display';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 140%;
        color: #2A254B;
    }
    &-elements{
        display: grid;
        grid-template-columns: repeat(4, 305px);
        justify-content: space-between;
        padding: 0 80px ;
    }
    &-element{
        margin-top: 110px;
        &__img{
            display:block; 
            margin-bottom: 12px;
        }
        &__title{
            margin:0 0 12px 0;
            font-family: 'Clash Display';
            font-style: normal;
            font-weight: 400;
            font-size: 20px;
            line-height: 140%;
            color: #2A254B;
        }
        &__price{
            color: #2A254B;
            font-size: 16px;
            line-height: 1.5;
            font-family: 'Satoshi';
            font-style: normal;
            font-weight: 400;
            font-size: 18px;
            line-height: 150%;
            color: #2A254B;
        }
    }
    &__links{
        display: flex;
        justify-content: center;
    }
    &__link{
            padding: 16px 32px;
            background: #F9F9F9;
            color: #2A254B;
            text-decoration: none;
            margin-top: 48px;
            align-items: center;
            &:hover{
                background: #f0f0f0;
                text-decoration: underline;
            }
    }
    }
    &__title{
        font-family: 'Clash Display';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 140%;
        color: #2A254B;
    }
    &-elements{
        display: grid;
        grid-template-columns: repeat(4, 305px);
        justify-content: space-between;
        padding: 0 80px ;
    }
    &-element{
        margin-top: 110px;
        &__img{
            display:block; 
            margin-bottom: 12px;
        }
        &__title{
            margin:0 0 12px 0;
            font-family: 'Clash Display';
            font-style: normal;
            font-weight: 400;
            font-size: 20px;
            line-height: 140%;
            color: #2A254B;
        }
        &__price{
            color: #2A254B;
            font-size: 16px;
            line-height: 1.5;
            font-family: 'Satoshi';
            font-style: normal;
            font-weight: 400;
            font-size: 18px;
            line-height: 150%;
            color: #2A254B;
        }
    }
    &__links{
        display: flex;
        justify-content: center;
    }
    &__link{
            padding: 16px 32px;
            background: #F9F9F9;
            color: #2A254B;
            text-decoration: none;
            margin-top: 48px;
            align-items: center;
            &:hover{
                background: #f0f0f0;
                text-decoration: underline;
            }
    }
}
</style>