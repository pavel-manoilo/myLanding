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
