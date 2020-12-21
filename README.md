Расширение для автоматической регистрации заявок (в ИАС Мониторинг)
===================================================================
Расширение для автоматической регистрации заявок отправленных в ИАС Мониторинг (для подсистем программного комплекса)

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist budanoff/yii2-register "*"
```

or add

```
"budanoff/yii2-register": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \budanoff\register\AutoloadExample::widget(); ?>```