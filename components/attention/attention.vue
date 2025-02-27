<template>
    <div class="attention">
        <div class="attention__action">
            <div class="action__slider"><img src="../../public/image/slider-image.png" alt="Slider"></div>
            <div class="action__offers">
                <div class="offer">
                    <p class="offers__cont"><span class="offer-vector">Бесплатно</span> доставим ваш заказ при покупке от 2000 ₽</p>
                    <img src="/public/image/offer-delivery.svg" alt="delivery">    
                </div>
                <div class="offer">
                    <p class="offers__cont">Скидка <br>при регистрации до <span class="offer-vector">15%</span></p>
                    <img src="/public/image/offer-sale.svg" alt="">
                </div>
            </div>
        </div>
        <div class="attention__popular">
            <h3 class="popular__head">Книга дня</h3>
            <div class="time">08:56:31</div>
            <img class="popular__book" src="/public/image/popular-book.svg" alt="">
            <p class="popular__book-genre">Корпоративное право</p>
            <h4 class="popular__book-title">Инвестирование: способы, риски, субъекты : монография</h4>
            <p class="popular__book-author">Майфат А.В.</p>
            <p class="popular__book-price">4 450 ₽</p>
            <div class="popular__button">
                <button class="popular__cart">В корзину</button>
                <button class="popular__favour"><img src="/public/image/popular-favour.svg" alt="favour"></button>
            </div>
        </div>
        <div class="action__offers-media">
                <div class="offer">
                    <p class="offers__cont"><span>Бесплатно</span> доставим ваш заказ при покупке от 2000 ₽</p>
                    <img src="/public/image/offer-delivery.svg" alt="delivery">    
                </div>
                <div class="offer">
                    <p class="offers__cont">Скидка <br>при регистрации до <span>15%</span></p>
                    <img src="/public/image/offer-sale.svg" alt="">
                </div>
            </div>
    </div>
</template>

<style>
    .attention{
        display: flex;
        justify-content: space-between;
        padding: 30px 113px;
        gap: 30px;
    }

    .attention__action
    {
        display: flex;
        flex-direction: column;
        max-width: 750px;
        gap: 30px;
    }

    .action__offers{
        display: flex;
        justify-content: space-between;
    }

    .action__offers-media{display: none;}

    .offer
    {
        display: flex;
        justify-content: space-between;
        flex-shrink: 0;
        flex-grow: 1;
        align-items: center;
        max-width: 360px;
        max-height: 140px;
        padding: 33px 25px;
        border-radius: 5px;
    }

        .offer:first-of-type .offer-vector{background: url(/public/image/offer-delivery-vector.svg) no-repeat; clip-path: none;}
        .offer:last-of-type .offers__cont{background: url(/public/image/offer-sale-vector.svg) no-repeat;}

    .offer img
    {
        width: 125px;
        height: 100px;
    }

    .offers__cont
    {
        font-family: 'Gosha Sans', serif;
        font-size: 20px;
        line-height: 25px;
        color: #ffffff;
    }

    .offer:last-of-type p{color: #1C294DCC;}

    /* .offer:first-of-type .offers__cont 
    {
        background-size: auto;
        background-position: 14px 43px;
        
    }

    .offer:last-of-type .offers__cont 
    {
        background: url(/public/image/offer-sale-vector.svg) no-repeat;
        background-size: auto;
        background-position: 20px 50px;
    } */

    .offer:first-of-type{background-color: #6D378F;}

    .offer:last-of-type{background-color: #FFD8EF;}

    .attention__popular
    {
        display: block;
        position: relative;
        width: 360px;
        background-color: #ffffff;
        border-radius: 5px;
        padding: 22px 20px;
    }

    .popular__head
    {
        font-size: 16px;
        font-weight: 500;
        line-height: 20px;
        color: #1C294D;
    }

    .time
    {
        position: absolute;
        top: 22px;
        right: 20px;
        font-size: 12px;
        line-height: 15px;
        font-weight: 500;
        color: #FF7A00;
        background-color: #FF7A0026;
        padding: 5px 10px;
    }

    .popular__book
    {
        margin: 23px auto 14px;
    }

    .popular__book-genre, 
    .popular__book-author
    {
        font-size: 12px;
        line-height: 15px;
        color: #1C294D80;
        margin-bottom: 7px;
    }

    .popular__book-title
    {
        font-weight: 500;
        line-height: 19px;
        color: #1C294D;
        margin-bottom: 10px;
    }

    .popular__book-price
    {
        font-size: 18px;
        font-weight: 700;
        line-height: 20px;
        margin-bottom: 12px;
    }

    .popular__button
    {
        display: flex;
        justify-content: flex-start;
    }

    .popular__cart
    {
        min-height: 40px;
        font-weight: 500;
        line-height: 15px;
        padding: 10px 25px 11px 55px;
        background: url('/public/image/popular-cart.svg') no-repeat 25px center;
        margin-right: 10px;
    }

    .popular__favour{padding: 10px;}

    .attention__popular button
    {
        border: 1px solid #EEEEEE;
        border-radius: 5px;
    }

    @media (max-width: 1140px) {
        .action__offers
        {
            display: block;
        }   
        
        .offer{max-width: 100%;}

        .offer:not(:last-child){margin-bottom: 20px;}

        .offer:last-of-type .offers__cont {background-position: 180px 25px;}

        .offer:first-of-type .offers__cont {background-position: 15px 44px;}
    }

     @media (max-width: 1024px) {
        .attention{padding: 0 90px; margin: 0 auto;}
    }

    @media (max-width: 968px) {
        .attention{padding: 30px;}
        .popular__cart{padding-left: 49px;}
    }

    @media (max-width: 768px) {
        .attention
        {
            display: flex;
            flex-direction: column; 
        }

        .attention__popular
        {
            width: 100%;
            margin: 0 auto;
        }

        .action__offers{display: none;}

        .action__offers-media{display: block;}
        
    }

    @media (max-width: 520px) {
        .attention{padding: 10px;}
        
    }

    @media (max-width: 375px) {
        .attention__popular{padding: 14px 20px 0;}
        .time{top: 12px;}
        .popular__book{max-width: 133px;}
        .popular__button{justify-content: space-between;}
        .popular__cart
        {
            flex-grow: 1;
            padding: 13px 25px 11px 55px;
            background-position: 84px center;
        }
        .popular__favour
        {
            width: 40px;
            flex-shrink: 0;
        }

        .offer:not(:last-child){margin-bottom: 10px;}

        .offer{padding: 33px 20px;}
    }
    
</style>