# Задача 10

[![](http://img-fotki.yandex.ru/get/6622/83739833.1f/0_9e219_a466f149_S.jpg)**Задача №10**](https://linkmeup.ru/blog/70.html)

Схема: как и для других задач по PBR. Конфигурация ниже.

Условие: ЛинкМиАп использует статические маршруты к провайдерам \(не BGP\).

На маршрутизаторе _msk-arbat-gw1_ настроена PBR: HTTP-трафик должен идти через провайдера Филькин Сертификат, а трафик из сети 10.0.2.0 должен идти через Балаган Телеком.  
Указанный трафик передается правильно, но не маршрутизируется остальной трафик из локальной сети, который должен передаваться через провайдера Балаган Телеком.

Задание:  
Исправить настройки таким образом, чтобы они соответствовали условиям.

Подробности задачи и конфигурация [тут](https://linkmeup.ru/blog/70.html)
