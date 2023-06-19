<template>
    <div class="about-brand">
        <h3 class="about-brand__title">What makes our brand different</h3>
    </div>
    <div class="about-brand-elements">
        <div class="about-brand-element"
        v-for="(element, i) of aboutbrand"
        :key="i">
            <img
            :src="element.img"
            alt="element.title"
            class="about-brand-element__img">
            <h4 class="about-brand-element__title">{{element.title}}</h4>
            <span class="about-brand-element__description">{{ element.description }}</span>
        </div>
    </div>
</template>

<script setup>
import {ref} from 'vue'

const aboutbrand = [
 {
    img:'/svg/aboud-brand_3.svg',
    title: 'Next day as standard',
    description: 'Order before 3pm and get your order the next day as standard'
 },
 {
    img:'/svg/aboud-brand_3.svg',
    title: 'Made by true artisans',
    description: 'Handmade crafted goods made with real passion and craftmanship'
 },
 {
    img:'/svg/aboud-brand_3.svg',
    title: 'Unbeatable prices',
    description: 'For our materials and quality you won’t find better prices anywhere'
 },
 {
    img:'/svg/aboud-brand_3.svg',
    title: 'Recycled packaging',
    description: 'We use 100% recycled to ensure our footprint is more manageable'
 },
]
</script>


<style lang="scss" scoped>
.about-brand {
    padding: 80px 80px 10px 0;
    &__title{
        font-family: 'Clash Display';
        font-weight: 400;
        font-size: 24px;
        line-height: 140%;
        color: #2A254B;
        text-align: center;
        margin: 0 0 84px 0;
    }
    &-elements{
        display: grid;
        grid-template-columns: repeat(4, 306px);
        justify-content: space-between;
        padding: 0 80px ;
    }
    &-element{
        background: #F9F9F9;
        padding: 48px 48px 48px 48px;
        &__img{
            display:block; 
            margin-bottom: 12px;
        }
        &__title{
            margin:0 0 12px 0;
            font-size: 20px;
            color: #2A254B;
        }
        &__description{
            color: #2A254B;
            font-size: 16px;
            line-height: 1.5;
        }
    }
}
</style>