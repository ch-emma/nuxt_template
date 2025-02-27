<template>
    <div class="footer">
        <div class="footer__form">
            <div class="footer__form-logotype">
                <div class="footer__form-logo"><a href="#" class="logo-link"><img src="/public/image/footer-logo.svg" alt="Logotype-Statut"></a></div>
                <form action="#" class="footer__form-edit">
                    <input type="e-mail" name="email-footer" class="footer-email" placeholder="Введите свой Email и получите скидку">
                    <input type="submit" name="submit-footer" class="footer-submit" value="">
                </form>
            </div>
            
            <div class="footer__social">
                <a href="#" class="footel__social-facebook">
                    <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M39.5 20C39.5 30.7696 30.7696 39.5 20 39.5C9.23045 39.5 0.5 30.7696 0.5 20C0.5 9.23045 9.23045 0.5 20 0.5C30.7696 0.5 39.5 9.23045 39.5 20Z" stroke="#282F36" stroke-opacity="0.15"/>
                    <path d="M24.6234 11.0037L22.2249 11C19.5302 11 17.7888 12.7387 17.7888 15.4298V17.4723H15.3771C15.1688 17.4723 15 17.6367 15 17.8395V20.7988C15 21.0016 15.1689 21.1658 15.3771 21.1658H17.7888V28.633C17.7888 28.8358 17.9575 29 18.1659 29H21.3124C21.5208 29 21.6896 28.8356 21.6896 28.633V21.1658H24.5093C24.7177 21.1658 24.8865 21.0016 24.8865 20.7988L24.8876 17.8395C24.8876 17.7421 24.8478 17.6489 24.7772 17.5799C24.7066 17.511 24.6103 17.4723 24.5103 17.4723H21.6896V15.7409C21.6896 14.9087 21.8933 14.4862 23.0073 14.4862L24.623 14.4857C24.8312 14.4857 25 14.3212 25 14.1186V11.3708C25 11.1683 24.8314 11.0041 24.6234 11.0037Z" fill="#282F36" fill-opacity="0.3"/>
                    </svg>
                </a>
                <a href="#" class="footel__social-vk">
                    <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M20 40C31.0457 40 40 31.0457 40 20C40 8.9543 31.0457 0 20 0C8.9543 0 0 8.9543 0 20C0 31.0457 8.9543 40 20 40Z" fill="#4C75A3"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M20 34C27.732 34 34 27.732 34 20C34 12.268 27.732 6 20 6C12.268 6 6 12.268 6 20C6 27.732 12.268 34 20 34Z" fill="white"/>
                    <path d="M20 6C12.2683 6 6 12.268 6 20C6 27.732 12.2683 34 20 34C27.7317 34 34 27.732 34 20C34 12.268 27.7317 6 20 6ZM27.1015 21.5141C27.7541 22.1515 28.4444 22.7513 29.0302 23.4545C29.2897 23.7656 29.5343 24.0873 29.7205 24.4491C29.9863 24.965 29.7463 25.5307 29.2845 25.5613L26.4164 25.5608C25.6756 25.6221 25.0861 25.3233 24.5891 24.8169C24.1924 24.4133 23.8243 23.9822 23.4422 23.5648C23.2861 23.3935 23.1217 23.2322 22.9258 23.1054C22.5348 22.851 22.195 22.9289 21.971 23.3374C21.7427 23.753 21.6906 24.2136 21.6688 24.6762C21.6376 25.3525 21.4337 25.5292 20.7551 25.561C19.3051 25.6289 17.9293 25.4089 16.6506 24.6779C15.5226 24.0331 14.6495 23.1231 13.8887 22.0928C12.4072 20.0842 11.2726 17.8797 10.2531 15.6119C10.0237 15.1012 10.1916 14.8279 10.755 14.8174C11.6911 14.7993 12.6272 14.8016 13.5633 14.8165C13.9443 14.8225 14.1963 15.0405 14.3427 15.4C14.8486 16.6446 15.4687 17.8287 16.2459 18.927C16.453 19.2194 16.6643 19.511 16.9654 19.7176C17.2977 19.9456 17.5509 19.8702 17.7076 19.4993C17.8078 19.2635 17.8511 19.0115 17.8729 18.7588C17.9473 17.8935 17.9562 17.0284 17.8273 16.1665C17.7471 15.6271 17.4438 15.2788 16.9061 15.1768C16.6323 15.125 16.6724 15.0236 16.8056 14.8672C17.0367 14.5968 17.2533 14.4295 17.6861 14.4295L20.9267 14.4289C21.4374 14.5292 21.552 14.7583 21.6213 15.2728L21.6241 18.874C21.6181 19.0731 21.7241 19.6631 22.0816 19.7935C22.368 19.888 22.5571 19.6583 22.7284 19.477C23.5055 18.6523 24.0592 17.6789 24.555 16.6715C24.7739 16.2272 24.9627 15.7675 25.146 15.3069C25.2823 14.9663 25.4943 14.7987 25.8787 14.8045L28.9992 14.8082C29.0912 14.8082 29.1846 14.809 29.2757 14.8248C29.8016 14.9147 29.9457 15.141 29.783 15.6541C29.5269 16.4601 29.0293 17.1315 28.5429 17.8047C28.0216 18.5254 27.4656 19.2209 26.9494 19.9447C26.4751 20.6064 26.5126 20.9395 27.1015 21.5141Z" fill="#4C75A3"/>
                    </svg>
                </a>
                <a href="#" class="footel__social-instagram">
                    <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M39.5 20C39.5 30.7696 30.7696 39.5 20 39.5C9.23045 39.5 0.5 30.7696 0.5 20C0.5 9.23045 9.23045 0.5 20 0.5C30.7696 0.5 39.5 9.23045 39.5 20Z" stroke="#282F36" stroke-opacity="0.15"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M19.9969 10.0059C17.2819 10.0059 16.9414 10.0174 15.8752 10.066C14.8111 10.1145 14.0844 10.2836 13.4485 10.5307C12.7912 10.7861 12.2337 11.128 11.6779 11.6837C11.1221 12.2395 10.7803 12.797 10.5248 13.4544C10.2777 14.0903 10.1087 14.817 10.0602 15.881C10.0115 16.9473 10 17.2877 10 20.0027C10 22.7177 10.0115 23.0581 10.0602 24.1244C10.1087 25.1884 10.2777 25.9151 10.5248 26.551C10.7803 27.2084 11.1221 27.7659 11.6779 28.3217C12.2337 28.8774 12.7912 29.2193 13.4485 29.4747C14.0844 29.7219 14.8111 29.8909 15.8752 29.9394C16.9414 29.988 17.2819 29.9995 19.9969 29.9995C22.7118 29.9995 23.0523 29.988 24.1185 29.9394C25.1826 29.8909 25.9093 29.7219 26.5452 29.4747C27.2025 29.2193 27.76 28.8774 28.3158 28.3217C28.8716 27.7659 29.2134 27.2084 29.4689 26.551C29.716 25.9151 29.885 25.1884 29.9335 24.1244C29.9822 23.0581 29.9937 22.7177 29.9937 20.0027C29.9937 17.2877 29.9822 16.9473 29.9335 15.881C29.885 14.817 29.716 14.0903 29.4689 13.4544C29.2134 12.797 28.8716 12.2395 28.3158 11.6837C27.76 11.128 27.2025 10.7861 26.5452 10.5307C25.9093 10.2836 25.1826 10.1145 24.1185 10.066C23.0523 10.0174 22.7118 10.0059 19.9969 10.0059ZM19.9969 11.8071C22.6661 11.8071 22.9823 11.8173 24.0364 11.8654C25.0111 11.9098 25.5404 12.0727 25.8927 12.2096C26.3593 12.3909 26.6923 12.6076 27.0421 12.9574C27.392 13.3072 27.6086 13.6402 27.79 14.1069C27.9269 14.4591 28.0897 14.9884 28.1342 15.9631C28.1823 17.0172 28.1925 17.3334 28.1925 20.0027C28.1925 22.672 28.1823 22.9882 28.1342 24.0423C28.0897 25.017 27.9269 25.5463 27.79 25.8986C27.6086 26.3652 27.392 26.6982 27.0421 27.048C26.6923 27.3978 26.3593 27.6145 25.8927 27.7958C25.5404 27.9327 25.0111 28.0956 24.0364 28.14C22.9825 28.1881 22.6663 28.1983 19.9969 28.1983C17.3274 28.1983 17.0113 28.1881 15.9573 28.14C14.9826 28.0956 14.4533 27.9327 14.101 27.7958C13.6344 27.6145 13.3013 27.3978 12.9515 27.048C12.6017 26.6982 12.3851 26.3652 12.2037 25.8986C12.0668 25.5463 11.904 25.017 11.8595 24.0423C11.8114 22.9882 11.8012 22.672 11.8012 20.0027C11.8012 17.3334 11.8114 17.0172 11.8595 15.9631C11.904 14.9884 12.0668 14.4591 12.2037 14.1069C12.3851 13.6402 12.6017 13.3072 12.9515 12.9574C13.3013 12.6076 13.6344 12.3909 14.101 12.2096C14.4533 12.0727 14.9826 11.9098 15.9573 11.8654C17.0114 11.8173 17.3276 11.8071 19.9969 11.8071Z" fill="#282F36" fill-opacity="0.3"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M19.9969 23.3359C18.1565 23.3359 16.6646 21.844 16.6646 20.0036C16.6646 18.1633 18.1565 16.6713 19.9969 16.6713C21.8372 16.6713 23.3291 18.1633 23.3291 20.0036C23.3291 21.844 21.8372 23.3359 19.9969 23.3359ZM19.9969 14.8701C17.1617 14.8701 14.8633 17.1685 14.8633 20.0036C14.8633 22.8388 17.1617 25.1371 19.9969 25.1371C22.832 25.1371 25.1304 22.8388 25.1304 20.0036C25.1304 17.1685 22.832 14.8701 19.9969 14.8701Z" fill="#282F36" fill-opacity="0.3"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M26.5328 14.6664C26.5328 15.329 25.9957 15.866 25.3331 15.866C24.6706 15.866 24.1335 15.329 24.1335 14.6664C24.1335 14.0039 24.6706 13.4668 25.3331 13.4668C25.9957 13.4668 26.5328 14.0039 26.5328 14.6664Z" fill="#282F36" fill-opacity="0.3"/>
                    </svg>
                </a>
                <a href="#" class="footel__social-twitter">
                    <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M39.5 20C39.5 30.7696 30.7696 39.5 20 39.5C9.23045 39.5 0.5 30.7696 0.5 20C0.5 9.23045 9.23045 0.5 20 0.5C30.7696 0.5 39.5 9.23045 39.5 20Z" stroke="#282F36" stroke-opacity="0.15"/>
                    <path d="M28.9801 14.6676C28.9558 14.6385 28.9156 14.6287 28.8813 14.6445C28.373 14.8725 27.8383 15.0364 27.2876 15.1332C27.8723 14.6885 28.3079 14.0728 28.5313 13.3667C28.5421 13.3329 28.5309 13.2959 28.5036 13.2739C28.4761 13.2519 28.438 13.2491 28.4078 13.2672C27.7493 13.6621 27.0362 13.9404 26.2871 14.0948C25.6234 13.3984 24.6966 13 23.7374 13C21.7866 13 20.1998 14.6044 20.1998 16.5765C20.1998 16.815 20.2226 17.0513 20.2678 17.2806C17.5659 17.112 15.0396 15.8005 13.3218 13.6703C13.3042 13.6485 13.2775 13.6364 13.2497 13.6392C13.222 13.6413 13.1973 13.6571 13.1833 13.6813C12.8699 14.2248 12.7043 14.8468 12.7043 15.4794C12.7043 16.576 13.1971 17.6012 14.0361 18.2777C13.6042 18.2252 13.1823 18.0877 12.8018 17.8742C12.7763 17.8596 12.7444 17.8598 12.7188 17.8747C12.6932 17.8895 12.677 17.917 12.6763 17.9469L12.676 17.9927C12.676 19.5675 13.7024 20.9502 15.1627 21.4093C14.778 21.472 14.379 21.4678 13.9867 21.3921C13.9578 21.3866 13.9275 21.3967 13.9076 21.4192C13.888 21.4417 13.8814 21.4732 13.8904 21.5017C14.3283 22.8836 15.545 23.8527 16.9613 23.9734C15.7799 24.8485 14.3835 25.3095 12.9081 25.3095C12.6363 25.3095 12.3626 25.2932 12.0944 25.2613C12.0561 25.2569 12.0182 25.28 12.0049 25.3171C11.9917 25.3546 12.0058 25.3965 12.0389 25.4178C13.6355 26.4531 15.4816 27 17.3779 27C23.5807 27 27.2872 21.9059 27.2872 16.9812C27.2872 16.8441 27.2846 16.7076 27.2792 16.5716C27.9483 16.0767 28.5228 15.471 28.9859 14.7698C29.0066 14.7385 29.0044 14.6968 28.9801 14.6676Z" fill="#282F36" fill-opacity="0.3"/>
                    </svg>
                </a>
            </div>
        </div>
        <div class="footer__nav">
            <div class="footer__nav-menu">
                <div class="nav__menu-row">
                    <ul class="nav__menu-list">
                        <h5 class="nav__menu-head">Покупателям</h5>
                        <li class="list__item"><a href="#" class="menu__link">Наша почта</a></li>
                        <li class="list__item"><a href="#" class="menu__link">Оплата и доставка</a></li>
                        <li class="list__item"><a href="#" class="menu__link">Вопросы и ответы</a></li>
                    </ul>
                </div>
                <div class="nav__menu-row">
                    <ul class="nav__menu-list">
                        <h5 class="nav__menu-head">Издательство</h5>
                        <li class="list__item"><a href="#" class="menu__link">О компании</a></li>
                        <li class="list__item"><a href="#" class="menu__link">Авторам</a></li>
                        <li class="list__item"><a href="#" class="menu__link">Вакансии</a></li>
                        <li class="list__item"><a href="#" class="menu__link">Контакты</a></li>
                    </ul>
                </div>
                <div class="nav__menu-row">
                    <ul class="nav__menu-list">
                        <h5 class="nav__menu-head">Книги</h5>
                        <li class="list__item"><a href="#" class="menu__link">Все категории</a></li>
                        <li class="list__item"><a href="#" class="menu__link">Бестселлеры</a></li>
                        <li class="list__item"><a href="#" class="menu__link">Новинки</a></li>
                        <li class="list__item"><a href="#" class="menu__link">Скидки и акции</a></li>
                    </ul>
                </div>
                <div class="nav__menu-row">
                    <ul class="nav__menu-list">
                        <h5 class="nav__menu-head">Прайс-лист</h5>
                        <li class="list__item footer-nav-file"><a href="/public/image/address.svg" download>Скачать прайс-лист<br><span class="footer-nav-file-size">PDF, 12 Mb</span></a></li>
                    </ul>
                </div>
                <div class="nav__menu-row">
                    <ul class="nav__menu-list">
                        <h5 class="nav__menu-head">Телефон и Email</h5>
                        <li class="list__item footer-nav-email"><a href="#">market@estatut.ru</a></li>
                        <li class="list__item footer-nav-tel"><a href="#">8 (968) 660-65-50</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer__nav-contact">
                <span class="footer__nav-publish">© 2020 Издательство «Статут»</span>
                <span class="footer__nav-addres">ул. Лобачевского, 92, корп. 2 119454, г. Москва</span>
                <div class="footer__nav-link">
                    <a href="#" class="footer__nav-privacy">Политика конфиденциальности</a>
                    <a href="#" class="footer__nav-agreement">Договор оферты</a>
                </div>
            </div>
        </div>

        <!-- media -->
        <div class="footer__nav-media">
            <div class="footer__menu-media footer__select-buyers">
                <select name="buyers" id="" value="Покупателям">
                    <option value="Покупателям">Покупателям</option>
                    <option value="Наша почта">Наша почта</option>
                    <option value="Оплата и доставка">Оплата и доставка</option>
                    <option value="Вопросы и ответы">Вопросы и ответы</option>
                </select>
            </div>
            <div class="footer__menu-media footer__select-publishing">
                <select name="publishing" id="" value="Издательство">
                    <option value="Наша почта" selected>Издательство</option>
                    <option value="Оплата и доставка">О компании</option>
                    <option value="Вопросы и ответы">Авторам</option>
                    <option value="Вопросы и ответы">Вакансии</option>
                    <option value="Вопросы и ответы">Контакты</option>
                </select>
            </div>
            <div class="footer__menu-media footer__select-books">
                <select name="books" id="" value="Книги">
                    <option value="Наша почта" selected>Книги</option>
                    <option value="Оплата и доставка">Все категории</option>
                    <option value="Вопросы и ответы">Бестселлеры</option>
                    <option value="Вопросы и ответы">Новинки</option>
                    <option value="Вопросы и ответы">Скидки</option>
                </select>
            </div>
            <div class="footer__menu-media footer__select-price">
                <select name="pricelist" id="" value="Прайс лист">
                    <option value="Наша почта" selected>Прайс лист</option>
                    <option value="Оплата и доставка"><a href="/public/image/address.svg" download>Скачать прайс-лист<br><span class="footer-nav-file-size">PDF, 12 Mb</span></a></option>
                </select>
            </div>
            <div class="footer__menu-document-media">
                <div class="footer__nav-privacy"><a href="#">Политика конфиденциальности</a></div>
                <div class="footer__nav-agreement"><a href="#">Договор оферты</a></div>
            </div>
            <div class="footer__menu-contacts-media">
                <div class="footer-nav-tel"><a href="#">8 (968) 660-65-50</a><a><img src="/public/image/info.svg" alt=""></a></div>                
                <div class="footer-nav-email"><a href="#">market@estatut.ru</a></div>
                <div class="footer__nav-addres"><span>ул. Лобачевского, 92, корп. 2 119454, г. Москва</span></div>
                <div class="footer__nav-publish"><span>© 2020 Издательство «Статут»</span></div>
            </div>
        </div>
    </div>
</template>

<style>
    .footer__form-logo
    {
        min-width: 50px;
        height: auto;
        margin-right: auto;
    }

    .footer__form
    {
        display: flex;
        justify-content: space-between;
        margin: 0 auto;
        padding: 22px 113px;
        background-color: #282F360A;
    }

    .footer__form-logotype
    {
        display: flex;
        justify-content: space-between;
    }

    .footer__social
    {
        display: flex;
        gap: 15px;
        margin-left: 49px;
    }

    .footer__form-edit
    {
        position: relative;
        display: flex;
        justify-content: center;
        margin: 0 auto;
    }

    .footer-email
    {
        padding: 9px 15px;
        min-width: 443px;
        border-radius: 5px;
    }

    .footer-submit
    {
        position: absolute;
        width: 50px;
        height: 40px;
        right: 0;
        background: #FF5C00 url('/public/image/footer_Send.svg') no-repeat center center;
        border-top-right-radius: 5px;
        border-bottom-right-radius: 5px;
    }

    .footer__nav-media{display: none;}

    .footer__nav{
        width:100%;
        background-color: #ffffff;
        padding: 49px 113px;
        color: #282F36CC;
    }

    .footer__nav-menu
    {
        display: flex;
        gap: 30px;
        width: 100%;
        border-bottom: 1px solid #282F3626;
        padding-right: 166px;
        padding-bottom: 40px;
    }

    .nav__menu-row
    {
        display: block;
        width: 165px;
    }

    .nav__menu-row:nth-of-type(4){width: auto;}

    .list__item:not(:last-child){margin-bottom: 15px;}

    .nav__menu-column
    {
        display: table-cell;
        padding-bottom: 14px;
    }
    
    .nav__menu-head
    {
        font-weight: 500;
        line-height: 20px;
        color: #1C294D;
        padding-bottom: 24px;
    }

    .footer-nav-file
    {
        width: auto;
        position: relative;
        background: url('/public/image/footer-download.svg') no-repeat left 4px;
        padding-left: 36px;
    }

    .footer-nav-file-size
    {
        font-size: 12px;
        line-height: 15px;
        color: #282F3680;
    }

    .footer-nav-email
    {
        background: url("/public/image/footer-email.svg") no-repeat 3px 3px;
        padding-left: 29px;
    }

    .footer-nav-tel
    {
        background: url('/public/image/footer-tel.svg') no-repeat 3px 0;
        padding-left: 29px;    
    }

    .footer__nav-publish
    {
        color: #1C294D80;
        line-height: 20px;
        margin-right: 140px;
    }

    .footer__nav-contact
    {
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        padding-top: 40px;
        padding-bottom: 45px;
    }

    .footer__nav-addres
    {
        margin: auto;
        color: #1C294D80;
    }

    .footer__nav-link
    {
        display: flex;
        gap: 30px;
    }

    .footer__nav-privacy
    {
        text-align: right;
        color: #1C294D80;
    }

    .footer__nav-agreement
    {
        text-align: right;
        color: #1C294D80;
    }

    @media (max-width: 1024px) {
        .footel__social{margin-left: auto;}        
    }

    @media (max-width: 768px) {
    .footer__form
    {
        display: flex;
        flex-direction: column-reverse;
        padding: 20px 55px;
    }

    .footer__form-logotype
    {
        padding-top: 20px;
        border-top: 1px solid #1C294D26;
    }

    .footer__form-logo
    {
        display: flex;
        justify-content: space-between;
    }

    .footer__social
    {
        margin: 0 auto;
        padding-bottom: 20px;
    }

    .footel__social-facebook svg 
    {
        fill: #3064CE;  
    }

    .footel__social-facebook svg path:last-of-type
    {
        fill: #ffffff;
        fill-opacity: 1;
    }

    .footel__social-vk svg
    {
        fill: #4C75A3;
    }

    .footel__social-vk svg path:nth-child(2)
    {
        fill: #ffffff;
        fill-opacity: 1;
    }

    .footel__social-twitter svg 
    {
        display: none;
    }

    .footel__social-instagram svg
    {
        fill: #E4405F;
    }

    .footel__social-instagram svg path:not(:first-of-type)
    {
        fill: #ffffff;
        fill-opacity: 1;
    }

    .footer__nav
    {
        display: none;
    }

    .footer__nav-media
    {
        display: block;
        width: 100%;
        background-color: #ffffff
    }

    .footer__menu-media
    {
        padding: 0 20px;
    }

    .footer__menu-media select
    {
        width: 100%;
        border-bottom: 1px solid #1C294D26;
        padding: 20px 0;
        font-size: 16px;
        line-height: 20px;
        color: #2A3D48;
    }

    .footer__select-price select{border-bottom: none;}

    .footer__menu-document-media
    {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        gap: 10px;
        padding: 20px;
        border-top: 1px solid #1C294D26;align-items: flex-start;
    }

    .footer__menu-document-media, 
    .footer__nav-publish
    {
        line-height: 20px;
        color: #1C294D80;
    }

    .footer__menu-contacts-media .footer-nav-tel
    {
        display: flex;
        padding: 20px 40px;
        border-top: 1px solid #1C294D26;
        background-position: 20px 20px;
        gap: 5px;
    }

    .footer-nav-email
    {
        padding: 20px 40px;
        border-top: 1px solid #1C294D26;
        background-position: 20px 23px;
    }

    .footer__nav-addres
    {
        padding: 20px 40px;
        color: #1C294D;
        border-top: 1px solid #1C294D26;
        border-bottom: 1px solid #1C294D26;
        background: url('/public/image/city.svg') no-repeat 20px 20px;
    }

    .footer__nav-publish
    {
        padding: 20px;
    }

    @media (max-width: 375px) 
    {
        .footer{padding-top: 24px;}
        .footer__form{padding: 20px;}
        .footer-email{min-width: 270px;}
        .footer__social{margin: 0 93px;}
        .footer__menu-media{padding: 0 22px 0 16px;}
        .footer__menu-document-media{padding: 17px 21px;}
        .footer__menu-contacts-media .footer-nav-tel
        {
            padding: 23px 45px;
            background-position: 21px 24px;
        }
        .footer-nav-email
        {
            padding: 16px 47px;
            background-position: 21px 19px;
        }
        .footer__nav-addres
        {
            padding: 23px 20px 23px 44px;
            background-position: 20px 23px;
        }
        .footer__nav-publish
        {
            margin: 0;
            padding: 17px 20px;
        }
    }
}
</style>