# HW-1

* Реализовать функцию get_transport(transport_name, host, port, login, passowrd) которая возвращаетет instance транспорта
Выбрасывает исключение UnknownTransport - в случае если трансопрта не существует.

* Реализовать класс тнаспрота SSH

```
exec(command) выполняет комманду на целвевом хосте в виде юникод строки  
get_file(path) возвращает содержимое файла
```
* Класс транспорта SSH выбрасывает исключения TransportError в случае остутвия комманды файла, TransportConnetionError - в случае ошибок подключения

* Написать тесты. (pytest или другие библиотеки)
