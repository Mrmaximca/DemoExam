Зайти с помощью локального пользователя:
```
.\Administrator
xxXX1234
```

Выполнить в CMD следующие команды:
Убрать второй IP адрес:
```
netsh interface ipv4 set interface 11 dadtransmits=0 store=persistent
```

Отключить безопасный режим:
```
bcdedit /deletevalue {current} safeboot
```

Выполнить перезагрузку:
```
shutdown /r /t 0
```
