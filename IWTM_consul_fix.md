1) Установить необходимый IP-адрес

2) Исправить файл /etc/hosts: изменить IP-адрес iwtm.demo.lab на установленный Вами

3) Открыть следующий файл:

```
/opt/iw/tm5/etc/consul/consul.json
```

4) Исправить строчку "bind_addr" на установленный Вами IP-адрес

5) Выполнить команду перезагрузки Traffic Monitor:

```
iwtm restart
```
