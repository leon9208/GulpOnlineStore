<h1>Пример разработки интернет-магазина с помощью Gulp</h1>
<h2>Описание</h2>
<p>В данном репозитории находится верстка интернет-магазина с помощью Gulp.</p>
<p>В шаблоне используются препроцессоры Pug и Stylus.</p>
<h2>Требования</h2>
<ol>
  <li>Node.js.</li>
  <li>Node.js Packet Manager (NPM).</li>
  <li>Gulp.</li>
  <li>Git.</li>
  <li>Git Bash &mdash; для пользователей Windows.</li>
  <li>Bower.</li>
</ol>
<h2>Использование</h2>
<p>1. Клонирование проекта:</p>
<pre>git clone https://github.com/mikorn/gulp-online-store.git --depth 1 my-gulp-online-store</pre>
<p>Далее необходимо перейти в папку проекта:</p>
<pre>cd my-gulp-online-store</pre>
<p>2. Установка npm-зависимостей:</p>
<pre>npm install</pre>
<p>Или:</p>
<pre>npm i</pre>
<p>3. Установка bower-зависимостей:</p>
<pre>bower install</pre>
<p>Или:</p>
<pre>bower i</pre>
<p>Проект готов для разработки</p>
<h2>Разработка</h2>
<p>Структура проекта:</p>
<pre>
project/
|------/app/
|----------/assets/
|-----------------/css/
|---------------------/common.min.css
|---------------------/common.css
|---------------------/vendor.min.css
|-----------------/fonts/
|-----------------/images/
|-----------------/js/
|--------------------/common.min.js
|--------------------/common.js
|--------------------/vendor.min.js
|----------/blocks/
|-----------------/block-1/
|-------------------------/block-1.js
|-------------------------/block-1.styl
|-----------------/block-2/
|-------------------------/block-2.js
|-------------------------/block-2.styl
|-----------------/block-3/
|-------------------------/block-3.js
|-------------------------/block-3.styl
|----------/materials/
|----------/pug/
|--------------/blocks/
|---------------------/footer.pug
|---------------------/head.pug
|---------------------/header.pug
|---------------------/sidebar.pug
|--------------/layouts/
|----------------------/default.pug
|--------------/pages/
|--------------------/404.pug
|--------------------/about.pug
|--------------------/contacts.pug
|--------------------/index.pug
|--------------------/services.pug
|----------/config/
|-----------------/mixins.styl
|-----------------/variables.styl
|----------/vendor/
|-----------------/bootstrap/
|-----------------/font-awesome/
|-----------------/jquery/
|-----------------/normalize-css/
|----------/404.html
|----------/about.html
|----------/contacts.html
|----------/index.html
|----------/services.html
|------/.bowerrc
|------/.gitignore
|------/bower.json
|------/gulpfile.js
|------/package.json
|------/dist/
|-----------/assets/
|------------------/css/
|----------------------/common.min.css
|----------------------/vendor.min.css
|------------------/fonts/
|------------------/images/
|------------------/js/
|---------------------/common.min.js
|---------------------/vendor.min.js
|-----------/404.html
|-----------/about.html
|-----------/contacts.html
|-----------/index.html
|-----------/services.html
|------/node_modules/
</pre>
<p>По умолчанию из внешних библиотек установлены jQuery, Normalize.css, Bootstrap, Font Awesome.</p>
<p>Данный список можно изменить с помощью Bower и внести соответствующие изменения в gulpfile.js. Далее перезапустить Gulp.</p>
<p>Для разработки необходимо запустить Gulp:</p>
<pre>gulp</pre>
<p>Вся разработка ведется в папке app.</p>
<p>Для формирования папки для production выполняется команда:</p>
<pre>gulp public</p>
