# Лабораторная работа №11

### Цель - изучение процесса создания сеансов совместной разработки с использованием инструмента ngrok

```$ sudo snap install ngrok``` - скачиваю ngrok
```$ ngrok config add-authtoken 2PKbzib3vbB0pJOeY3faOrNxOCL_5nFREJMsewBF1Nfgg467t``` - Добавляю свой токен в ngrok.yml для удобной работы с сервисом
```$ sudo apt-get install openssh-server``` - скачиваю сервер 
```$ sudo systemctl start ssh``` - запускаю
```$ sudo systemctl status ssh``` - проверяю
новое окно консоли
```$ python3 -m http.server``` - распакова модуля http.server 
новое окно консоли
```$ nano index.html``` - создаю
```$ ngrok tcp 22``` - запускаю TCP туннель

***ssh 6.tcp.eu.ngrok.io -p 12977*** 
