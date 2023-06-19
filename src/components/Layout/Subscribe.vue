<template>
    <div class="subscribe">
        <div class="subscribe-form">
            <input type="text" placeholder="your@email.com" class="subscribe-text" >
            <button class="subscribe-btn">Sign up</button>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.subscribe{
    background: url("/img/subscript.jpg");
    background-size: cover;
    margin-top: 60px;
    height: 445px;
    display: flex;
    justify-content: center;
    align-items: center;
    &-text{
       padding: 17px 205px 17px 32px;
       font-family: 'Satoshi';
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 22px;
        border: none;
        &:focus{
            outline: none;
        }
    }
    &-btn{
        padding: 16px 32px; 
        background: #2A254B; 
        color: #fff;
        font-family: 'Satoshi';
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 150%;
        cursor: pointer;
        border: none;
        &:hover{
            opacity: 0.8;
        }
       }
    &-form{
       margin-top: 230px;
       
    }
    
    

}
</style>