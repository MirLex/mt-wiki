# Системные требования

В зависимости от того, как будет использоваться Movable Type, системные требования будут отличаться. Тем не менее, минимальные рекомендованные характеристики следующие:

* 1 GHz CPU;
* 512 Мб оперативной памяти;
* 100 Мб свободного дискового пространства для Movable Type и генерируемых файлов.

Примечание: для системных файлов Movable Type необходимо приблизительно 20 Мб, остальное место на диске необходимо для генерируемых файлов и загружаемого медиа (картинки, документы и другие файлы).

## Операционная система 

Платформа Movable Type протестирована на следующих операционных системах:

* Windows XP Professional, Service Pack 2
* Windows Server 2003, Service Pack 2
* Mac OS X 
* Все основные Unix-системы, включая: 
    * Solaris, SunOS
    * RedHat Enterprise, Fedora и CentOS
    * Linux
    * BSD

Movable Type быстрее всего работает на Unix-системах, поэтому рекомендуется выбирать сервер или хостинг именно с этими операционными системами.

## Perl 

Movable Type отлично работает с Perl 5.8.1 и выше. С другими версиями Perl MT также будет работать, но официально поддерживаемая версия — 5.8.1.

## Веб-сервер 

Для работы MT необходим веб-сервер, на котором возможно выполнение CGI-скриптов. Если вы хотите использовать динамическую публикацию, то веб-сервер также должен поддерживать PHP. Следующие веб-серверы протестированы и корректно работают с Movable Type:

* Apache 1.3x, Apache 2.x
* IIS 5.x, IIS 6.x (Windows-платформа)

Примечание: Movable Type поддерживает mod_perl 1.x, но не поддерживает mod_perl 2.x.

## PHP 

Movable Type поддерживает статическую и динамическую публикацию. Для динамической публикации необходимо наличие PHP версии 4 и выше (рекомендуется 5-я версия).

## База данных 

Movable Type 4 отлично поддерживает следующие базы данных:

* MySQL 4.0 и выше
* PostgreSQL 7.x, PostgreSQL 8.x
* SQLite

Movable Type 5 поддерживает работу только с MySQL.

## Браузер 

Movable Type отлично работает в следующих браузерах:

* Safari 2.x
* Safari 3.x
* Firefox 2.x
* Firefox 3.x
* IE6
* IE7+

Примечание: Movable Type работает отлично и в браузере Opera 9, 10 и 11, но в некоторых случаях некорректно работает подсветка синтаксиса в шаблонах и визуальный редактор записей.