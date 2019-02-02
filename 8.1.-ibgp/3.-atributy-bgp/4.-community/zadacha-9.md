# Задача 9

[![](http://img-fotki.yandex.ru/get/6622/83739833.1f/0_9e219_a466f149_S.jpg)**Задача № 9**](https://linkmeup.ru/blog/101.html)  
Одним из наших клиентов стала крупная компания. Платят они нам довольно много, но тут возникла проблема с тем, что когда происходят какие-то проблемы с провайдером AS64501, то качество связи, которую обеспечивает линк с провайдером AS64502, не устраивает клиента. Главное для нашего клиента, хорошее качество связи к филиалам.  
Так как клиент солидный, то пришлось установить пиринг с еще одним провайдером AS64513\. Но он нам дорого обходится поэтому использовать его мы будем только когда провайдер AS64501 недоступен и только для этого важного клиента.  
Задание:  
Надо настроить работу сети таким образом, чтобы через провайдера AS64513 сеть клиента 150.0.0.0/24 анонсировалась только в том случае, если через провайдера AS64501 недоступна сеть 103.0.0.0/22 (она используется для проверки работы провайдера). Кроме того, от провайдера AS64513 нам надо принимать только сети филиалов клиента (50.1.1.0/24, 50.1.2.0/24, 50.1.3.0/24) и использовать их только если они недоступны через провайдера AS64501\. Остальной трафик клиента будет ходить через AS64502.  
Конфигурация: [базовая](https://docs.google.com/document/d/1Nd2qWdLNUd1WyO1Q-U3UKZu4W3LJk8BQYlACfVCjz-I/pub).  
Подробности задачи [тут](https://linkmeup.ru/blog/101.html).  