<template>
    <div class="footer">
        <div class="footer-content">
            <div class="footer-top">
                <div class="footer-menu">
                    <div class="footer-menu-column">
                        <span class="footer-menu__title">Menu</span>
                        <a href="#" class="footer-menu__link">New arrivals</a>
                        <a href="#" class="footer-menu__link">Best sellers</a>
                        <a href="#" class="footer-menu__link">Recently viewed</a>
                        <a href="#" class="footer-menu__link">Popular this week</a>
                        <a href="#" class="footer-menu__link">All products</a>
                    </div>
                    <div class="footer-menu-column">
                        <span class="footer-menu__title">Categories</span>
                        <a href="#" class="footer-menu__link">Crockery</a>
                        <a href="#" class="footer-menu__link">Furniture</a>
                        <a href="#" class="footer-menu__link">Homeware</a>
                        <a href="#" class="footer-menu__link">Plant pots</a>
                        <a href="#" class="footer-menu__link">Chairs</a>
                        <a href="#" class="footer-menu__link">Crockery</a>
                    </div>
                    <div class="footer-menu-column">
                        <span class="footer-menu__title">Our company</span>
                        <a href="#" class="footer-menu__link">About us</a>
                        <a href="#" class="footer-menu__link">Vacancies</a>
                        <a href="#" class="footer-menu__link">Contact us</a>
                        <a href="#" class="footer-menu__link">Privacy</a>
                        <a href="#" class="footer-menu__link">Returns policy</a>
                    </div>
                </div>
                <div class="footer-subscribe">
                    <span class="footer-subscribe__title">Join our mailing list</span>
                    <div class="footer-subscribe__form">
                        <input type="text" placeholder="your@email.com" class="footer-subscribe-text" >
                        <button class="footer-subscribe-btn">Sign up</button>
                    </div>
                </div>
            </div>
            <div class="footer-bottom">
                <span class="footer-bottom__copyright">Copyright 2022 Avion LTD</span>
                <div class="footer-bottom-socials">
                    <a href="#" class="footer-bottom-socials__link"><img src="/svg/in.svg" alt=""></a>
                    <a href="#" class="footer-bottom-socials__link"><img src="/svg/facebook.svg" alt=""></a>
                    <a href="#" class="footer-bottom-socials__link"><img src="/svg/instagram.svg" alt=""></a>
                    <a href="#" class="footer-bottom-socials__link"><img src="/svg/skype.svg" alt=""></a>
                    <a href="#" class="footer-bottom-socials__link"><img src="/svg/twitter.svg" alt=""></a>
                    <a href="#" class="footer-bottom-socials__link"><img src="/svg/pinterest.svg" alt=""></a>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.footer{
    background: #2A254B;
    color: #fff;
    &-content{
        padding: 58px 82px 25px 82px;
    }
    &-top{
        display: grid;
        grid-template-columns: 540px 1fr;
        column-gap: 110px;
        border-bottom: 1px solid #4E4D93;
    }
    &-menu{
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        margin-bottom: 48px;
        &__title{
            display: block;
            margin-bottom: 12px;
            font-family: 'Clash Display';
            font-style: normal;
            font-weight: 400;
            font-size: 16px;
            line-height: 20px;
            color: #FFFFFF;
        }
        &__link{
            display: block;
            color: #fff;
            text-decoration: none;
            font-size: 14px;
            margin-bottom: 12px;
            &:last-child{
                margin-bottom: 0;
            }
            &:hover{
                text-decoration: underline;
            }
        }
    }
    &-subscribe{
        &__title{
            font-family: 'Clash Display';
            font-style: normal;
            font-weight: 400;
            font-size: 16px;
            line-height: 20px;
            color: #FFFFFF;
        }
        &__form{
            margin-top: 16px;
        }
    }
    &-bottom{
        padding-top: 22px;
        display: flex;
        justify-content: space-between;
        &__copyright{
            font-style: 14px;
        }
        &-socials{
            display: flex;
            align-items: center;
            &__link{
                margin: 0 12px;
                &:hover{
                    opacity: 0.8;
                }
            }
        }
    }
.footer-subscribe-text{
    padding: 17px 205px 16px 32px;
       font-family: 'Satoshi';
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 22px;
        background: rgba(255, 255, 255, 0.15);
        color: #fff;
        border: none;
        &:focus{
            outline: none;
        }
    }
.footer-subscribe-btn{
    padding: 15px 32px; 
    background: #FFFFFF;
    color: #2A254B;
    cursor: pointer;
        font-family: 'Satoshi';
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 150%;
        border: none;
        &:hover{
            opacity: 0.8;
        }
}    
}
</style>