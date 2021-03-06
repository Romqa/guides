Начать работу с Ember.js очень просто. Разработчики создают и управляют проектами Ember.js через программу командной строки Ember CLI. Она предоставляет:

* Современное управление ресурсами приложения (включая комбинирование, минимизацию и контроль версий).
* Встроенные генераторы, которые помогут создавать компоненты, маршруты и т. д.
* Общепринятый макет проекта, что позволяет легко связывать приложения Ember.js от разных разработчиков.
* Поддержку ES2015/16 JavaScript через проект [Babel](http://babeljs.io/docs/learn-es2015/). Сюда входит и поддержка [модулей JavaScript](http://exploringjs.com/es6/ch_modules.html), которые используются в руководстве.
* Завершенное средство тестирования [QUnit](https://qunitjs.com/).
* Доступ к растущей экосистеме Ember Addons.

## Зависимости

### Node.js и npm

Ember CLI создана на JavaScript, и ей нужна среда выполнения [Node.js](https://nodejs.org/). Также ей требуются зависимости, извлеченные через [npm](https://www.npmjs.com/). npm упакован с Node.js, и если на вашем компьютере уже установлен Node.js, то вы готовы к использованию Ember.  

Для Ember нужен Node.js 0.12 или выше и npm 2.7 или выше. Если вы не уверены, стоит ли у вас Node.js, то наберите в командной строке следующее:

```bash
node --version
npm --version
```

В выводе появится номер версии. Если вместо этого вы получите ошибку *"command not found"* (команда не найдена) или устаревшая версия Node:

* Пользователи Windows или Mac OS могут просто загрузить и запустить [установщик Node.js](http://nodejs.org/download/).
* Пользователи Mac OS обычно ставят Node с помощью [Homebrew](http://brew.sh/). После установки Homebrew наберите команду `brew install node` для установки Node.js.  
* Пользователи Linux могут использовать [это руководство по установке Node.js на Linux](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager).

Если у вас устаревшая версия npm, то запустите `npm install -g npm`. 
  
### Git

Ember нужен Git, чтобы управлять большинством зависимостей. Git есть в Mac OS X и многих дистрибутивах Linux. Пользователи Windows могут загрузить и запустить [установщик Git](http://git-scm.com/download/win).

### Watchman (опционально)

На Mac OS и Linux вы можете повысить эффективность отслеживания файлов, если установите [Watchman](https://facebook.github.io/watchman/docs/install.html).

### PhantomJS (опционально)

Вы можете запускать тесты из командной строки с помощью PhantomJS и без необходимости держать браузер открытым. Ознакомьтесь с [инструкциями по загрузке PhantomJS](http://phantomjs.org/download.html).

## Установка 

Устанавливайте Ember через npm:

```bash
npm install -g ember-cli 
```

Чтобы проверить, как прошла установка, запустите команду:

```bash
ember -v
```

Если в ответ вы получите номер версии, то все прошло успешно.