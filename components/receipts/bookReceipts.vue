<template>
    <div class="receipts">
        <div class="receipts__head">
            <div class="head__cell" rowspan="3">
                <h3>Новые поступления</h3>
            </div>
            <div class="head__cell">
                <div class="head__cell-butscroll">
                    <button class="head__cell-but" value=""></button>
                    <button class="head__cell-but" value=""></button>
                </div>
                
            </div>
        </div>
        <div class="receipts__books">
                <div class="books__cell">
                    <img class="receipts__book" src="/public/image/receipts-book -1.jpg" alt="">
                    <p class="receipts__book-genre popular__book-genre">Корпоративное право</p>
                    <h4 class="receipts__book-title popular__book-title">Инвестирование: способы, риски, субъекты : монография</h4>
                    <p class="receipts__book-author popular__book-author">Майфат А.В.</p>
                    <p class="receipts__book-price popular__book-price">4 450 ₽</p>
                    <div class="rating">
                        <div class="book__rating-evaluation"><img src="/public/image/receip-star.svg" alt="">4.9</div>
                        <div class="book__rating-recommend"><img src="/public/image/receip-class.svg" alt="">89% рекомендуют</div>
                    </div>
                    <div class="book__cell-buttons">
                        <button class="book__cart-btn"><img src="/public/image/popular-cart.svg" alt="">В корзину</button>
                        <button class="book__favour-btn"><img src="/public/image/favorites.svg" alt="favour"></button>
                </div>
            </div>
            <div class="vertical-line"></div>
            <div class="books__cell">
                <img class="receipts__book" src="/public/image/receipts-book-2.jpg" alt="">
                <p class="receipts__book-genre popular__book-genre">Договорное право</p>
                <h4 class="receipts__book-title popular__book-title">Договор коммерческой концессии (франчайзинг). Граж...</h4>
                <p class="receipts__book-author popular__book-author">Багдасарян А.Ф.</p>
                <p class="receipts__book-price popular__book-price">372 ₽</p>
                <div class="rating">
                    <div class="book__rating-evaluation"><img src="/public/image/receip-star2.svg" alt="">4.9</div>
                    <div class="book__rating-recommend"><img src="/public/image/receip-class.svg" alt="">89% рекомендуют</div>
                </div>
                <div class="book__cell-buttons">
                    <button class="book__cart-btn"><img src="/public/image/popular-cart.svg" alt="">В корзину</button>
                    <button class="book__favour-btn"><img src="/public/image/popular-favour.svg" alt="favour"></button>
                </div>
            </div>
            <div class="vertical-line"></div>
            <div class="books__cell">
                <img class="receipts__book" src="/public/image/receipts-book-3.jpg" alt="">
                <p class="popular__book-genre popular__book-genre">Конкурентное право</p>
                <h4 class="receipts__book-title popular__book-title">Договор коммерческой концессии (франчайзинг). Граж...</h4>
                <p class="receipts__book-author popular__book-author">Башлаков-Николаев И.В.</p>
                <p class="receipts__book-price popular__book-price"><span class="sale-price">984 ₽</span><span class="old-price">1 284 ₽</span><span class="benefit">Выгода 30%</span></p>
                <div class="rating">
                    <div class="book__rating-evaluation"><img src="/public/image/receip-star2.svg" alt="">4.9</div>
                    <div class="book__rating-recommend"><img src="/public/image/receip-class.svg" alt="">89% рекомендуют</div>
                </div>
                <div class="book__cell-buttons">
                    <button class="book__cart-btn"><img src="/public/image/popular-cart.svg" alt="">В корзину</button>
                    <button class="book__favour-btn"><img src="/public/image/popular-favour.svg" alt="favour"></button>
                </div>
            </div>
            <div class="vertical-line"></div>
            <div class="books__cell">
                <img class="receipts__book" src="/public/image/receipts-book -1.jpg" alt="">
                <p class="popular__book-genre popular__book-genre">Корпоративное право</p>
                <h4 class="receipts__book-title popular__book-title">Инвестирование: способы, риски, субъекты : монография</h4>
                <p class="receipts__book-author popular__book-author">Майфат А.В.</p>
                <p class="receipts__book-price popular__book-price">450 ₽</p>
                <div class="rating">
                    <div class="book__rating-evaluation"><img src="/public/image/receip-star2.svg" alt="">4.9</div>
                    <div class="book__rating-recommend"><img src="/public/image/receip-class.svg" alt="">89% рекомендуют</div>
                </div>
                <div class="book__cell-buttons">
                    <button class="book__cart-btn"><img src="/public/image/popular-cart.svg" alt="">В корзину</button>
                    <button class="book__favour-btn"><img src="/public/image/popular-favour.svg" alt="favour"></button>
                </div>
            </div>
        </div>
        <div class="receipts__more">
                <a href="#" class="more__cell-text">Показать все книги раздела</a>
        </div>
    </div>
</template>

<style>
    .receipts
    {
        display: flex;
        flex-direction: column;
        max-width: 1140px;
        margin: 0 auto;
        background-color: #ffffff;
        border-collapse: collapse;
        margin-bottom: 30px;
    }

    .receipts__head
    {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 14px 25px;
        font-size: 20px;
        font-weight: 700;
        line-height: 25px;
        color: #1C294D;
        border-bottom: 1px solid #1C294D26;
    }

    .head__cell
    {
        vertical-align: middle;
    }

    .head__cell-but{
        position: relative;
        border: 1px solid #1C294D26;
        border-radius: 5px;
        padding: 10px;
        width: 30px;
        height: 30px;
        text-align: right;
    }

    .head__cell-butscroll
    {
        display: flex;
        justify-content: flex-end;
        align-content: center;
    }

    .head__cell-but::before{
        content: "";
        position: absolute;
        width: 5.53px;
        height: 5.53px;
        border-bottom: 1px solid #1C294D;
        border-right: 1px solid #1C294D;
        top: 11px;
        left: 11px;
    }

    .head__cell-but:first-of-type:before{rotate: 135deg;}
    .head__cell-but:last-of-type:before{rotate: -45deg;}

    .receipts__books
    {
        display: flex;
        justify-content: space-between;
        border-bottom: 1px solid #1C294D26;
    }

    .receipts__book-title
    {
        display: inline-block;
        width: 223px;
        height: 38px;
        overflow: hidden;
        text-overflow: ellipsis;
        margin-bottom: 3px;
    }
/* 
    .books__cell:not(:last-child)
    {
        position: relative;
    } */

    .vertical-line{
        border-right: 1px solid #1C294D26;
    }

    /* .books__cell:nth-child(4n){border-right: none;}
    .books__cell:nth-child(4n+1){border-left: none;} */

    .books__cell:nth-child(1)::before, .books__cell:nth-child(4)::before
    {
        content: "Бестселлер";
        position: absolute;
        width: 86px;
        height: 25px;
        border-radius: 5px;
        background: #EEE9F7;
        color: #AC8EE3;
        padding: 5px 10px;
        font-size: 12px;
        font-weight: 500;
        top: 18px;
    }

    .books__cell:nth-child(1)::after, .books__cell:nth-child(4)::after
    {
        content: "1+1=3";
        position: absolute;
        width: 56px;
        height: 25px;
        border-radius: 5px;
        background-color: #FFEEEE;
        color: #FF4F52;
        padding: 5px 10px;
        top: 53px;
        font-size: 12px;
        font-weight: 500;
    }

    .books__cell:nth-child(2)::before
    {
        content: "Новинка";
        position: absolute;
        font-size: 12px;
        font-weight: 500;
        color: #3DC47E;
        background-color: #E2F6EC;
        top: 18px;
        width: 70px;
        height: 25px;
        border-radius: 5px;
        padding: 5px 10px;
    }

    .receipts__book
    {
        margin: 0 auto 15px;
    }

    .book__cell-buttons
    {
        display: flex;
        gap: 10px;
    }

    .book__cell-buttons button
    {
        display: flex;
        justify-content: start;
        border: 1px solid #EEEEEE;
        border-radius: 5px;
        gap: 10px;
    }

    .book__cart-btn
    {
        padding: 10px 25px;
    }

    .book__favour-btn
    {
        padding: 10px;
    }

    .old-price
    {
        position: relative;
        font-size: 12px;
        font-weight: 400;
        line-height: 15px;
        color: #1C294D80;
        margin-right: 7px;
    }

    .old-price::before
    {
        content: "";
        position: absolute;
        width: 41px;
        border-bottom: 1px solid #FD3A3A;
        top: 7px;
        rotate: -5deg;
    }

    .benefit
    {
        font-size: 12px;
        line-height: 14.06px;
        font-weight: 400;
        color: #0DB98C;
    }

    .sale-price
    {
        margin-right: 7px;
        color: #FD3A3A;
    }

    .rating
    {
        display: flex;
        gap: 10px;
        margin-bottom: 6px;
    }

    .book__rating-evaluation
    {
        padding: 5px 8px;
        color: #FBC02D;
        background-color: rgba(251, 192, 45, 0.15);
    }

    .book__rating-recommend
    {
        padding: 5px 10px;
        background-color: rgba(121, 134, 203, 0.15);
        color: rgba(121, 134, 203, 1);
    }

    .book__rating-evaluation,
    .book__rating-recommend
    {
        display: flex;
        justify-content: flex-start;
        border-radius: 5px;
        font-size: 12px;
        vertical-align: middle;
        gap: 5px;
    }

    .receipts__more
    {
        width: 100%;
        padding: 10px;
        font-size: 14px;
        line-height: 20px;
        font-weight: 500;
        color: #1C294D;
        text-align: center;
    }

    @media (max-width: 1140px) {
        .books__cell:last-child{display: none;}        
    }

    @media (max-width: 1024px) {
        .content{padding: 0 75px; margin: 0 auto;}

        .books__cell:last-of-type, .vertical-line:last-of-type{display: none;}

        .receipts
        {
            display: flex;
            margin: 0 auto;
        }
    }

    @media (max-width: 768px) {
        .receipts
        {
            display: flex;
            padding: 30px 30px;
            margin: 0 auto;
        }

        .books__cell:nth-last-of-type(3){display: none;}
        .books__cell:nth-last-of-type(3) + .vertical-line{display: none;}

    }

    @media (max-width: 520px) {

        .receipts{padding: 10px;}

        .books__cell
        {
            padding-left: 10px;
            padding-right: 10px;
        }
        
        .vertical-line{display: none;}
    }

    @media (max-width: 320px) {
        .books__cell:nth-of-type(2){display: none;}
        .books__cell:nth-of-type(2) + .vertical-line{display: none;}
    }

</style>