# myStartTemplate
Start template (Gulp + Webpack) for Pug, SCSS, JS, Vue

## Установка / Install
* установите / install [NodeJS](https://nodejs.org/en/) и / and [Yarn](https://yarnpkg.com/en/docs/install) (если требуется) / (if you need)
* установите / install [Git](https://gicm.com/downloads) и перейдите на репозиторий шаблона / and open template repository ````https://github.com/SharyginNikita/myStartTemplate.git````
* нажмите на кнопку / press on button ````use this template```` (Также вы можете форкнуть репозиторий / aslo you can fork repository)
* склонируйте репозиторий используя SSH ключ (рекомендуется) / clone repository used SHH key (recommended)````git@github.com:SharyginNikita/myStartTemplate.git````
* перейдите в скачанную папку со сборкой: / change directory on template ````cd myStartTemplate````
* инициализируйте репозиторий / init repository ````yarn init````
* скачайте необходимые зависимости: / download required dependencies ````yarn````
* чтобы начать работу, введите команду: / start work use command ````yarn gulp````

## Команды / Command
* ````yarn gulp```` (Сборка и запуск сервера в режиме development / Build & run server in development mode)
* ````yarn gulp --prod```` (Сборка в режиме production / Build & run server in production mode)
* ````yarn gulp build-dev```` (Сборка в режиме development / Build in development mode)
* ````yarn gulp build-prod```` (Сборка в режиме production / Build in production mode)
* ````yarn gulp testPug```` линтинг Pug файлов / lint Pug files
* ````yarn gulp clear```` удалить все / delete all html, css, js, img файлы из соответсвующих папок / files from them folder (смотреть / check gulpfile.js и / and config.js)
* Отдельные таски можно посмотреть в / other task you can see in gulpfile.js