<template>
    <div class="newsletter">
        <form action="#" class="newsletter__form">
            <label for="email" class="form__label">Скидка 200 ₽ при подписке на рассылку Издательства</label>
            <input type="email" name="e-mail" id="email" class="form__email" placeholder="Введите ваш Email">
            <input type="submit" name="subscribe-but" id="subscribe" class="form__but-subscribe" value="Подписаться">
        </form>
    </div>
</template>

<style>
    .newsletter
    {
        max-width: 1140px;
        margin: 0 auto;
        border-radius: 5px;
        color: #ffffff;
        padding: 32px 45px;
        background:  url("/public/image/newsletter-vector.svg") #0288D1 no-repeat;
        background-position: 100px 38px;
        margin-bottom: 30px;
    }

    .newsletter__form{
        display: flex;
        justify-content: space-between;
        align-items: baseline;
    }

    .form__label
    {
        font-size: 18px;
        font-weight: 500;
        line-height: 20px;
        margin-right: 14px;
        white-space: nowrap;
    }

    .form__email
    {
        width: 100%;
        padding: 10px 15px;
        font-size: 14px;
        line-height: 20px;
        font-weight: 400;
        border-radius: 5px;
        margin-right: 10px;
    }

    .form__but-subscribe
    {
        padding: 10px 25px;
        border: 1px solid #ffffff;
        border-radius: 5px;
        font-size: 14px;
        line-height: 20px;
        font-weight: 500;
    }

    @media (max-width: 968px) {
        .newsletter{background-position: 100px 28px;}

        .newsletter form
        {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }   

        .form__label{white-space: wrap;}

        .form__but-subscribe{width: 100%;}
    }

    @media (max-width: 520px) {
        .newsletter
        {
            padding: 20px;
            margin-bottom: 0;
        }
        .newsletter form 
        {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .form__label
        {
            max-width: 335px;
        }

        .form__but-subscribe{width: 100%;}
    }
    
    @media (max-width: 375px) {
        .newsletter
        {
            margin: 0 10px;
            padding: 20px 10px;
            background-position: 65px 18px;
        }
        .form__label
        {
            max-width: 270px;
            white-space: normal;
            line-height: 25px;
        }
    }
</style>