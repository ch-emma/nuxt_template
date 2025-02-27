<template>
    <div class="news">
        <div class="news__header">
            <h3>Новости</h3>
            <div class="news__header-butscroll">
                <button class="news__header-but" value=""></button>
                <button class="news__header-but" value=""></button>
            </div>
        </div>
        <div class="news__content">
            <div class="news__item">
                <img src="/public/image/news-img1.jpg" alt="">
                <span class="news__item-date">16 июня 2020</span>
                <div><p class="news__item-head">Бесплатный онлайн-семинар. Доктрина stare decisis: борьба за прецедент в рос...</p></div>
                <div><p class="news__item-description">18 июня в «Клубе цивилистов» пройдет бесплатный онлайн-семинар по проблематике судебного прецедента. Мероприятие приуроч...</p>
                </div>
                <button class="news__item-but">Читать</button>
            </div>
            <div class="news__item">
                <img src="/public/image/news-img2.png" alt="">
                <span class="news__item-date">16 июня 2020</span>
                <div><p class="news__item-head">Бесплатный онлайн-семинар. Доктрина stare decisis: борьба за прецедент в рос...</p></div>
                <div><p class="news__item-description">18 июня в «Клубе цивилистов» пройдет бесплатный онлайн-семинар по проблематике судебного прецедента. Мероприятие приуроч...</p>
                </div>
                <button class="news__item-but">Читать</button>
            </div>
            <div class="news__item">
                <img src="/public/image/news-img3.jpg" alt="">
                <span class="news__item-date">16 июня 2020</span>
                <div><p class="news__item-head">Бесплатный онлайн-семинар. Доктрина stare decisis: борьба за прецедент в рос...</p></div>
                <div><p class="news__item-description">18 июня в «Клубе цивилистов» пройдет бесплатный онлайн-семинар по проблематике судебного прецедента. Мероприятие приуроч...</p>
                </div>
                <button class="news__item-but">Читать</button>
            </div>
        </div>
    </div>
</template>

<style>
    .news
    {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        max-width: 1140px;
        margin: 0 auto;
        background-color: #ffffff;
        margin-bottom: 30px;
    }

    .news__header
    {
        display: flex;
        justify-content: space-between;
        border-bottom: 1px solid #1C294D26;
        padding: 15px 25px;
    }

    .news h3
    {
        font-size: 20px;
        font-weight: 700;
        line-height: 25px;
        color: #1C294D;
    }

    .news__header-butscroll
    {
        display: flex;
        justify-content: flex-end;
        align-content: center;
        
    }

    .news__header-but
    {
        position: relative;
        border: 1px solid #1C294D26;
        border-radius: 5px;
        padding: 10px;
        width: 30px;
        height: 30px;
        text-align: right;
    }

    .news__header-but::before
    {
        content: "";
        position: absolute;
        width: 5.53px;
        height: 5.53px;
        border-bottom: 1px solid #1C294D;
        border-right: 1px solid #1C294D;
        top: 11px;
        left: 11px;
    }

    .news__header-but:first-of-type::before{rotate: 135deg;}
    .news__header-but:last-of-type::before{rotate: -45deg;}

    .news__content
    {
        display: flex;
        justify-content: space-between;
        padding: 25px 20px;
    }

    .news__item
    {
        /* padding-right: 35px; */
    }

    .news__item:not(:nth-child(3n))
    {
        padding-right: 35px;
        border-right: 1px solid #1C294D26;
        margin-right: 35px;
    }

    .news__item img{margin-bottom: 15px;}

    .news__item-date
    {
        font-size: 12px;
        font-weight: 400;
        line-height: 15px;
        color: #1C294D80;
        margin-top: 15px;
        margin-bottom: 5px;
    }

    .news__item-head
    {
        font-size: 16px;
        font-weight: 500;
        line-height: 20px;
        color: #1C294D;
        max-width: 320px;
        max-height: 40px;
        overflow: hidden;
        margin-bottom: 8px;
    }

    .news__item-description
    {
        font-size: 14px;
        font-weight: 400;
        line-height: 20px;
        color: #1C294D;
        overflow: hidden;
        margin-bottom: 12px;
    }

    .news__item-but
    {
        padding: 10px 66px;
        border: 1px solid #1C294D26;
        border-radius: 5px;
        font-weight: 500;
        line-height: 20px;
    }

    @media (max-width: 768px) {
        .news__item:last-of-type{display: none;}
    }

    @media (max-width: 375px) {
        .news__item:not(:first-child){display: none;}
        .news__item:first-child
        {
            width: 100%;
            margin: 0 auto; 
            padding: 0;
            border-right: none;
        }

        .news__item-but{width: 100%;}

        .news__header{padding: 10px 20px;}

        .news__item img {margin-bottom: 20px;}
    }
</style>