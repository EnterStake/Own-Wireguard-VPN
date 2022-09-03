# Own Wireguard VPN
#

WireGuard - бесплатное программное приложение с открытым исходным кодом, протокол виртуальной частной сети (VPN) для передачи данных в зашифрованном виде и создания безопасных соединений
1. Арендуем сервер (Можно взять с минимальными характеристиками) 
2. Запускаем скрипт, который установить все необходимое:

```sh
wget https://git.io/wireguard -O wireguard-install.sh && bash wireguard-install.sh
```
3. Порт оставляем по умолчанию
4. Пишем название сервиса. Например:
 ```sh
 ownvpn
 ```
8. Выбираем DNS по умолчанию
9. Ожидаем установку, если установка завершилась удачно, высветится QR код/ Если QR код не появляется, пролистайте в конец статьи и найдите решение этой проблемы. Ошибка возникает на новой VPS, хостер после деплоя запускает скрипт обновления. Поэтому иногда просто стоит подождать минут 10, чтобы сервер обновился и можно повторить запуск скрипта.


