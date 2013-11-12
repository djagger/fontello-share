# Fontello-share

__Version__: 0.0.1

 Share buttons with your css. Based on __Yandex-share__ and __Fontello__.

## How to use

1. clone this repo `git clone https://github.com/tsarbas/fontello-share.git`
2. add css file `<link rel="stylesheet" href="fontello-share.css">`
3. add yandex-share block into html body
`<script type="text/javascript" src="http://yandex.st/share/share.js"
charset="utf-8"></script>`
`<div class="yashare-auto-init" data-yashareL10n="ru" data-yashareType="none" data-yashareQuickServices="vkontakte,facebook,twitter,odnoklassniki,moimir,gplus"></div>`
4. write your css
`
.b-share__handle.b-share__link {
    color: #ccc;
}
`