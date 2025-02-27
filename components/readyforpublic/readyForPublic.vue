<template>
    <div class="readyForPublic">
        <div class="readyForPublic__head">
            <div class="head__cell" rowspan="3">
                <h3>Готовятся к выходу</h3>
            </div>
            <div class="head__cell">
                <div class="head__cell-butscroll">
                    <button class="head__cell-but" value=""></button>
                    <button class="head__cell-but" value=""></button>
                </div>
                
            </div>
        </div>
        <div class="readyForPublic__books">
                <div class="books__cell">
                    <img class="readyForPublic__book" src="/public/image/receipts-book -1.jpg" alt="">
                    <p class="readyForPublic__book-genre popular__book-genre">Корпоративное право</p>
                    <h4 class="readyForPublic__book-title popular__book-title">Инвестирование: способы, риски, субъекты : монография</h4>
                    <p class="readyForPublic__book-author popular__book-author">Майфат А.В.</p>
                    <p class="readyForPublic__book-price popular__book-price">4 450 ₽</p>
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
                <img class="readyForPublic__book" src="/public/image/receipts-book-2.jpg" alt="">
                <p class="readyForPublic__book-genre popular__book-genre">Договорное право</p>
                <h4 class="readyForPublic__book-title popular__book-title">Договор коммерческой концессии (франчайзинг). Граж...</h4>
                <p class="readyForPublic__book-author popular__book-author">Багдасарян А.Ф.</p>
                <p class="readyForPublic__book-price popular__book-price">372 ₽</p>
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
                <img class="readyForPublic__book" src="/public/image/receipts-book-3.jpg" alt="">
                <p class="popular__book-genre popular__book-genre">Конкурентное право</p>
                <h4 class="readyForPublic__book-title popular__book-title">Договор коммерческой концессии (франчайзинг). Граж...</h4>
                <p class="readyForPublic__book-author popular__book-author">Башлаков-Николаев И.В.</p>
                <p class="readyForPublic__book-price popular__book-price"><span class="sale-price">984 ₽</span><span class="old-price">1 284 ₽</span><span class="benefit">Выгода 30%</span></p>
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
                <img class="readyForPublic__book" src="/public/image/receipts-book -1.jpg" alt="">
                <p class="popular__book-genre popular__book-genre">Корпоративное право</p>
                <h4 class="readyForPublic__book-title popular__book-title">Инвестирование: способы, риски, субъекты : монография</h4>
                <p class="readyForPublic__book-author popular__book-author">Майфат А.В.</p>
                <p class="readyForPublic__book-price popular__book-price">450 ₽</p>
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
        <div class="readyForPublic__more">
                <a href="#" class="more__cell-text">Показать все книги раздела</a>
        </div>
    </div>
</template>

<style>
    .readyForPublic
    {
        display: flex;
        flex-direction: column;
        max-width: 1140px;
        margin: 0 auto;
        background-color: #ffffff;
        border-collapse: collapse;
        margin-bottom: 30px;
    }

    .readyForPublic__head
    {
        display: flex;
        justify-content: space-between;
        padding: 17px 26px 12px;
        font-size: 20px;
        font-weight: 700;
        line-height: 25px;
        color: #1C294D;
        border-bottom: 1px solid #1C294D26;
    }

    .head__cell
    {
        display: flex;
        vertical-align: middle;
    }

    .head__cell-but{
        position: relative;
        border: 1px solid #1C294D26;
        padding: 10px;
        width: 30px;
        height: 30px;
        text-align: right;
    }

    .head__cell-but:first-child
    {
        border-top-left-radius: 5px;
        border-bottom-left-radius: 5px;
    }

    .head__cell-but:last-child
    {
        border-top-right-radius: 5px;
        border-bottom-right-radius: 5px;
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

    .readyForPublic__books
    {
        display: flex;
    }

    .readyForPublic__book-title
    {
        width: 156px;
        height: 55px;
        display: -webkit-box;
        -webkit-box-orient: vertical;
        -webkit-line-clamp: 3;
        overflow: hidden;
        text-overflow: ellipsis;
        margin-bottom: 3px;
    }

    .books__cell
    {
        display: block;
        position: relative;
        margin-left: 15px;
        margin-right: 14px;
        padding: 26px 20px 20px ;
    }

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

    .readyForPublic__book
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

    .readyForPublic__more
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
        .readyForPublic
        {
            margin: 0 auto;
        }
        
        /* .books__cell:last-child{display: none;}         */
    }

    @media (max-width: 1024px) {
        .readyForPublic
        {
            margin: 0 auto;
        }

        .readyForPublic__books{justify-content: space-between;}

        /* .books__cell:last-of-type, 
        .vertical-line:last-of-type
        {display: none;} */
    }

    @media (max-width: 768px) {
        .readyForPublic
        {
            margin: 0 auto;
        }
    }

    @media (max-width: 520px) {
        .readyForPublic
        {
            padding: 10px;
        }

        .books__cell{
            padding: 0 10px;
            max-width: 260px;
        }

        .books__cell:first-child{
            margin-right: 10px;}

        .books__cell:last-child{margin-left: 10px;}
    }

    @media (max-width: 375px) {
        .readyForPublic__books
        {
            max-width: 355px;
            padding: 0 11px;
        }
        .books__cell
        {
            padding: 20px 0 ;
            max-width: 180px;
            margin-left: 0;
        }
        .books__cell:not(:first-child):not(:last-child){display: none;}
 
        .vertical-line:not(:first-of-type)
        {display: none;}

        .rating{flex-direction: column;}

        .readyForPublic__book 
        {
            margin: 0 auto 15px;
            max-width: 126px;
        }

        .readyForPublic__head{padding: 16px 10px 12px;}

        .readyForPublic__book-title{margin-bottom: 11px;}

        .readyForPublic__book-price
        {
            margin-bottom: 5px;
        }
        .book__rating-evaluation
        {
            width: fit-content;
            padding: 5px 7px;
        }
        .book__rating-recommend{padding: 5px 12px;}

        .rating{gap: 5px;}

        .book__cell-buttons, 
        .book__cell-buttons button
        {
            align-items: center;
            gap: 5px;
        }

        .book__cart-btn
        {
            padding: 8px 10px;
            font-size: 14px;
            line-height: 15px;
            font-weight: 500;
        }

        .book__favour-btn{padding: 8px;}
    }

</style>