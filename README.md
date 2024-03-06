# Лабараторная работа №3
### Цель работы
* Данная лабораторная работа призвана напомнить основные команды ОС Debian/Ubuntu. Также она позволит познакомиться с Docker и его основными командами.
### Задание
* Запустить контейнер Ubuntu, установить Web-сервер Apache и вывести в браузере страницу с текстом "Hello, World!".
### Откройте терминал в папке containers03 и выполните команду:
![V1](https://github.com/IvanRazdorognii/container03/assets/159126939/4030a63c-5f98-4e21-9177-4caefea06652)
![V2](https://github.com/IvanRazdorognii/container03/assets/159126939/c5485f0d-ba3c-4939-8516-de5ed1b14dc8)
### В открывшемся окне выполните следующие команды и объясните их назначение:apt updateapt; install apache2 -y; service apache2 start.
#### apt update: Обновляет локальную базу данных пакетов, обеспечивая актуальную информацию о доступных версиях программного обеспечения.
#### apt install apache2 -y: Устанавливает веб-сервер Apache2 на вашей системе, флаг -y указывает на автоматическое подтверждение всех запросов во время установки, что упрощает процесс.
#### service apache2 start: Запускает службу Apache2, делая ваш веб-сервер доступным для обработки запросов от клиентов.
![V1](https://github.com/IvanRazdorognii/container03/assets/159126939/7a1b6bfe-a87e-4ba7-b66a-689afd52f466)
![V2](https://github.com/IvanRazdorognii/container03/assets/159126939/365fd22b-2aec-438e-869f-e1ac6537937a)
![V3](https://github.com/IvanRazdorognii/container03/assets/159126939/0ac1612a-94e9-4d32-925a-038d1cd83920)
![V4](https://github.com/IvanRazdorognii/container03/assets/159126939/59d7d432-a54e-46fc-b23e-b5147a5c64fd)
### Откройте браузер и введите в адресной строке http://localhost:8000. Что вы видите?
![Снимок экрана 2024-03-06 112730](https://github.com/IvanRazdorognii/container03/assets/159126939/9bcce5e1-4d40-4d27-8883-94a9be00a55a)
### Выполните следующие команды: ls -l /var/www/html/; echo '< h1>Hello, World!</ h1>' > /var/www/html/index.html.### Обновите страницу в браузере. Что вы видите?
* При обновлении страницы появляется выражение "Hello world".
### Выполните следующие команды:cd /etc/apache2/sites-enabled/; cat 000-default.conf
![1](https://github.com/IvanRazdorognii/container03/assets/159126939/77afb792-2a3c-4bb7-a40d-a7095766a899)
![2](https://github.com/IvanRazdorognii/container03/assets/159126939/bccd20bf-e2e2-4491-85ce-81e3163cea94)
# Вывод о проделанной работе:
#### Данная работа напомнила мне основные команды ОС Debian/Ubuntu, я вывел в браузере страницу с текстом "Hello, World!" и ознакомился с основными командами Docker.







