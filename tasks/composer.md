Composer
=====
Цель задания: изучить возможности composer и научиться применять их в реальных условиях

#### Документация и литература:
- официальная [документация](http://getcomposer.org/doc/)
- [статья](http://habrahabr.ru/post/145946/) на Хабре
- [composer workflow](http://adamcod.es/img/posts/composer-install-flow.png)

#### Вопросы для закрепления материала:
- что такое composer? зачем он нужен?
- как подключить стороннюю библиотеку через composer?
- зачем нужно свойство `minimum-stability`?
- в чем разница между свойствами `require` и `require-dev`
- зачем нужен файл `composer.lock`?
- в чем разница между командами `install` и `update`?
- как обновить одну конкретную зависимость из ранее установленного множества зависимостей?
- зачем нужен ресурс [packagist.org](http://packagist.org)?
- какие виды автозагрузки поддерживает composer? какая между ними разница?
- как подключить стороннюю библиотеку, не являющуюся composer package?
- как создать свой собственный composer package?

#### Задание 1:
- создать новый репозиторий
- подключить несколько сторонних библиотек на выбор через composer
- написать скрипт с примером использования подключенных библиотек

#### Задание 2:
- подключить ранее разработанный генератор ряда Фибоначчи не используя ресурс [packagist.org](http://packagist.org)
- продемонстрировать корректную работу подключеной библиотеки

#### Задание 3:
- переработать библиотеку с генератором и фильтром таким образом, что бы ее можно было подключить через composer используя ресурс [packagist.org](http://packagist.org)
- подключить переработаную библиотеку через composer с использованием ресурса [packagist.org](http://packagist.org)
