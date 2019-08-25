My landing page

В нашей работе используются такие font-family как :
dosis-light-webfont
dosis-regular-webfont
opensans-light-webfont
opensans-regular-webfont

Так же для заголовков h1,h2,h3,h4,h5,h6 глобально мы применяем такие значения :
    margin: 0 0 7px;
    font-family: 'dosisregular', sans-serif;
    font-weight: normal;
    text-transform: uppercase;

Лишь для первой секции (main-section) мы применяем container-fluid для которого у нас установлены такие парамертры : 
    margin: 0 auto;
    width: 100%;
    padding: 0 15px;

Во всех остальных случаях мы используем container с такими стилями :
    margin: 0 auto;
    width: 100%;
    max-width: 1200px;
    padding: 0 15px;

На все рисунки (img) мы применили :
    max-width: 100%;
    display: inline-block;
    vertical-align: middle;           

И лишь в секции portfolio мы им задали width : 100% чтобы все смотрелось приемлимо.

Для таких секций как services portfolio ,а так же для слайдера в секции slide_section мы используем  .tabs








@media (max-width: 660px) {




@media (max-width: 425px) {
    .bg_section {
        height: 455px;
        line-height: 455px;
    }
    .banner_title {
        line-height: 60px;
        margin-left: 30px;
    }
    
    .title-container {
        padding: 35px;
        margin: 0px 10px;
    }
    .input_holder textarea { 
        width: 100%;
    }
    .contact_section .col-3 {
        width: 100%;
    }
    .portfolio_list li {
        display: block;
        width: calc(100% /4);
        text-align: center;
        margin: 0 auto;
    }

    #portfolio_tabs .row .col-3 {
        width: 100%;
    }

    .latest_news_section .col-md-2 {
        width: 100%;
    }