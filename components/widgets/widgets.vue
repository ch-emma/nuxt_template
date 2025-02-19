<template>
    <div class="widgets">
        <div class="widgets__item item__1">
            <!-- <img src="/public/image/widget-fast.svg" alt=""> 
            <div class="widget__content"> -->
                <h4>Быстрая доставка</h4>
                <p>Доставим бесплатно <br>от 2000 ₽ по всей России</p>
            <!-- </div> -->
        </div>
        <div class="widgets__item item__2">
            <!-- <img src="/public/image/widget-secure-payment.svg" alt="">
            <div class="widget__content"> -->
                <h4>Безопасная оплата</h4>
                <p>Плати безопасно и легко онлайн на нашем сайте.</p>
            <!-- </div> -->
        </div>
        <div class="widgets__item item__3">
            <!-- <img src="/public/image/widget-bonus-program.svg" alt="">
            <div class="widget__content"> -->
                <h4>Бонусная  программа</h4>
                <p>Дополнительная скидка 15% при регистрации</p>
            <!-- </div> -->
        </div>
        <div class="widgets__item item__4">
            <!-- <img src="/public/image/widget-large-selection.svg" alt="">
            <div class="widget__content"> -->
                <h4>Большой выбор</h4>
                <p>Ежегодно выходит в свет более 100 книг</p>
            <!-- </div> -->
        </div>
    </div>
</template>

<style>
    .widgets
    {
        display: flex;
        max-width: 1140px;
        margin: 0 auto;
        justify-content: space-between;
        gap: 30px;
        margin-bottom: 30px;
    }

    .widgets__item
    {
        max-width: 263px;
        padding: 42px 20px 20px 90px;
        background-color: #FFFFFF;
        border-radius: 5px;
    }

    .widgets__item p
    {
        font-size: 12px;
        font-weight: 400;
        line-height: 19px;
        color: #727272;
    }

    .widgets__item h4{
        font-size: 16px;
        font-weight: 700;
        line-height: 25px;
        color: #1C294D;
        margin-bottom: 3px;
    }

    .item__1
    {
        background: url('/public/image/widget-fast-delivery.svg') #FFFFFF no-repeat left 35px; 
        padding: 41px 20px 42px 90px;
    }   
    .item__2
    {
        background: url('/public/image/widget-secure-payment.svg') #FFFFFF no-repeat 6px 41px;
        padding: 40px 20px 20px 96px;
    }   
    .item__3
    {
        background: url('/public/image/widget-bonus-program.svg') #FFFFFF no-repeat 3px 37px;
        padding: 40px 10px 42px 93px;
    }   
    .item__4
    {
        background: url('/public/image/widget-large-selection.svg') #FFFFFF no-repeat left 27px;
        padding: 40px 20px 42px 90px;
        }   
</style>