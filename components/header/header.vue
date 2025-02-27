<template>
    <div class="content">
		<div class="header">
			<div class="header__contact">
                <div class="header__contact-left">
                    <div class="city"><a href="#" class="city__link">Москва</a></div>
                    <div class="delive"><a href="#" class="delive__link">Доставка и оплата</a></div>
                    <div class="address"><a href="#" class="address__link">Адрес и часы работы</a></div>
                </div>
				<div class="header__contact-right">
                    <div class="email"><a href="#" class="email__link">market@estatut.ru</a></div>
                    <div class="phone"><a href="#" class="phone__link">8 (968) 660-65-50</a></div>
                    <div class="info"><a href="" class="info__link"><img src="/public/image/info.svg" alt=""></a></div>
                </div>
			</div>
            <hr>
			<div class="header__navigation">
                <div class="header__nav">
                    <a href="#" class="header__burger"><img src="/public/image/katalog.svg" alt=""></a>
                    <a href="#" class="logotype"><img src="../../public/image/statut-logo.svg" alt="Statut.ru"></a>
                    <div class="header_nav-search">
                        <input type="text" name="search" placeholder="Автор, название, ISBN">
                        <button class="btn-search"><img src="../../public/image/search.svg" alt="">Искать</button>
                    </div>
                    <div class="header__nav-user-block">
                        <a href="#" class="header__favorites">Отложено</a>
                        <a href="#" class="header__favorites header__favorites-media"></a>
                        <a href="#" class="header__signin">Войти</a>
                        <a href="#" class="header__signin header__signin-media"></a>
                        <a href="#" class="header__cart">Корзина</a>
                        <a href="#" class="header__cart header__cart-media"></a>
                    </div>
                </div>
                <div class="header__menu">
                    <nav class="header__nav-menu">
                        <ul class="nav__menu">
                            <li class="nav__link katalog">Каталог</li>
                            <li class="nav__link">Авторы</li>
                            <li class="nav__link">Новинки</li>
                            <li class="nav__link sale">Скидки</li>
                            <li class="nav__link">Партнерам</li>
                            <li class="nav__link">Мы</li>
                        </ul>
                    </nav>
                </div>
			</div>
		</div>
    </div>
</template>

<style>
    .content
    {
        position: relative;
        padding: 0 113px;
        background-color: #fff;
    }

	hr{
        position: absolute;
        color: #DFE0E1;
        width: 100%;
        left: 0;
	}

	.header{
		display: block;
        width: 100%;
        box-sizing: content-box;
	}

	.header__contact
	{
		display: flex;
        padding: 15px 0;
		justify-content: space-between;
	}

	.header__contact div{
		display: flex;
        min-width: auto;
        justify-content: space-between;
	}

    .header__contact div div{
        display: flex;
        justify-content: space-between;
    }

    .header__contact-left div:not(:last-child), .email {margin-right: 30px;}

	.city__link
	{
		padding-left: 25px;
		background: url('/public/image/city.svg') no-repeat left center;
	}

	.delive__link
	{
		padding-left: 25px;
		background: url('/public/image/delivery.svg')no-repeat left center;
	}

	.address__link
	{	
		padding-left: 25px;
		background: url('/public/image/address.svg')no-repeat left center;
	}

	.email__link{
		font-weight: 500;
		padding-left: 25px;
		background: url('/public/image/email.svg')no-repeat left center;
	}

	.phone__link
	{
		font-weight: 500;
		position: relative;
		padding-left: 25px;
        margin-right: 5px;
		background: url('/public/image/phone.svg')no-repeat left center;
	}

    .header__navigation{
        display: block;
        padding: 20px 0;
    }

    .header__nav{
        display: flex;
    }

    .header__nav-menu{display: flex;}

    .logotype{
        min-width: 43.75px;
        margin-right: 30px; 
    }

    .header__burger{display: none;}

    .header_nav-search{
        display: flex;
        justify-content: space-between;
        width: 573px;
        border: 1px solid #DFE0E1;
        border-radius: 5px;
        padding-left: 15px;
    }

    .btn-search{
        display: flex;
        padding: 10px 23px;
        background-color: #FF7A00;
        color: #fff;
        border-top-right-radius: 5px;
        border-bottom-right-radius: 5px;
    }

    .header_nav-search img{
        margin-right: 6px;
    }

    .header__nav-user-block{
        display: flex;
        gap: 33px;
        align-items: center;
        margin-left: auto;
    }

    .header__nav-user-block a{padding-left: 23px;}

    .header__cart-media,
    .header__signin-media,
    .header__favorites-media
    {display: none;}

    .header__favorites{background: url('/public/image/favorites.svg') no-repeat left center;}
    .header__signin{background: url('/public/image/signIn.svg') no-repeat left center;}
    .header__cart
    {
        position: relative;
        background: url('/public/image/cart.svg') no-repeat left center;
    }

    .header__cart::before
    {
        content: "10";
        position: absolute;
        width: 15px;
        height: 15px;
        border-radius: 50%;
        background-color: #FF7A00;
        color: #fff;
        text-align: center;
        padding-top: 1px;
        font-size: 9px;
        top: -7px;
        left: 10px;
    }

    .header__nav{
        margin: 0;
    }

    .nav__menu{
        display: flex;
        justify-content: space-between;
        padding-top: 18px;
        padding-left: 0;
    }

    .nav__link{
        margin-right: 25px;
    }

    .katalog{
        background: url('/public/image/katalog.svg') no-repeat left center;
        padding-left: 25px;
    }

    .sale{
        background: url('/public/image/sale.svg') no-repeat left center;
        color: #FF283D;
        padding-left: 25px;
    }

    @media (max-width: 1140px) {
        .content{padding: 0 90px; margin: 0 auto;}
    }

    @media (max-width: 1024px) {
        .content{padding: 0 75px; margin: 0 auto;}
        .header__contact div div a
        {
            text-align: center;
            padding: 25px 0;
            background-position: top center;
        }
    }

    @media (max-width: 870px) {
        .header_nav-search button {display: none;}

        .header_nav-search
        {
            position: relative;
            background-color: #f7f7f7;
            color: #1C294D80;
        }

        .header_nav-search input
        {
            background-color: #f7f7f7;
        }

        .header_nav-search::before
        {
            content: "";
            position: absolute;
            width: 20px;
            height: 20px;
            top: 7px;
            right: 10px;
            background: url('/public/image/header-serach-media.svg') no-repeat;
        }
    }

    @media (max-width: 768px) {
        .content{padding: 0 50px; margin: 0 auto;}

        .header__nav
        {
            display: flex;
            justify-content: space-between;
            gap: 20px;
        }

        .logotype{margin: 0;}

        .header__contact,
        .header__favorites, 
        .header__signin,
        .header__cart{display: none;}
        
        .header__favorites-media,
        .header__signin-media,
        .header__cart-media
        {
            display: block;
            width: 20px;
            height: 20px;
        } 
            
        .header__cart-media{background: url('/public/image/cart.svg') no-repeat left center;}
        .header__favorites-media{background: url('/public/image/favorites.svg') no-repeat left center;}
        .header__signin-media{background: url('/public/image/signIn.svg') no-repeat left center;}
    }

    @media (max-width: 600px) {
        .header__favorites-media,
        .header__signin-media{display: none;}   
        
        .header__menu{display: none;}

        .header__nav{gap: 10px;}

        .header__burger{display: flex; width: 35px;}
    }

    @media (max-width: 520px) {
        .content{padding: 0 10px; margin: 0 auto;}
    }
    
    @media (max-width: 375px) {
        .content{padding: 0 20px;} 
        
        .header__nav{gap: 15px;}

        .header__navigation{padding: 17px 0;}

        .header__burger
        {
            min-width: 20px;
        }
        .logotype{margin-right: 5px;}
        .header_nav-search::before{right: 17px;}
    }
</style>