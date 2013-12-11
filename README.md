Программа обучения мега-php-разработчика

Git + GitHub
=====

Цель задания изучить принципы работы с github и git через консоль. 

#### Документация и литература:
- докуметация по Git [здесь](http://git-scm.com/documentation)
- help по GitHub [здесь](https://help.github.com/)

#### Вопросы для закрепления материала:
- как создать новый репозиторий?
- что такое клонирование репозитория, как им пользоваться?
- как добавить новый файл в репозиторий?
- что такое .gitignore и как им пользоваться?
- что такое branch?
- как создать новый branch?
- как стянуть свежие изменения из remote ветки?
- что такое merge веток и как им пользоваться?
- в каком случае может возникнуть конфликт при сливании (merge) веток и как этот конфликт исправить?
- что такое stash, как им пользоваться?
- что такое pull request'ы, зачем они нужены, как с ними работать?
- что делает команда `git branch -d` и в чем ее отличие от `git branch -D`?

#### Задание:
Разработка каждой фичи должна вестись в отдельной ветке, после проверки работоспособности фичи ветку разработки необходимо мерджить с preproduction-веткой.

- создать новый публичный репозиторий
- написать генератор числовой последовательности Фибоначчи, который в качестве параметра принимает порядок, до которого генерировать ряд и возвращает массив чисел
- написать скрипт example.php с примером использования генератора
- написать фильтр нечетных чисел, который в качестве параметра принимает массив целых чисел и возвращает массив нечетных чисел
- добавить в example.php пример фильтрации числовой последовательности Фибоначчи
- по окончании работы над всеми фичами создать pull request, назначить его на своего ментора и выполнить все его требования


Composer
=====
Цель задания: изучить возможности composer и научиться применять их в реальных условиях

#### Документация и литература:
- официальная [документация](http://getcomposer.org/doc/)
- [статья](http://habrahabr.ru/post/145946/) на Хабре

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



Zend Framework
=====
Soon
