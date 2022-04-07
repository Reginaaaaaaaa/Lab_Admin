## Стартуем

Последовательность действий для запуска нашего плэйбука

```
vagrant up
```
Запускаем плэйбук

```
ansible-playbook ha_proxy.yml
```
## Тестируем

Сначала заходим на кастомную страницу и убеждаемся, что все работает

<a href="https://ibb.co/Ss3mYtD"><img src="https://i.ibb.co/QbKHSP7/Screenshot-from-2022-04-07-11-38-43.png" alt="Screenshot-from-2022-04-07-11-38-43" border="0"></a>


Теперь заходим на один из серверов, а после роняем его
Пробуем подключиться снова и вуаля, нас автоматически кинуло на второй сервер

<a href="https://ibb.co/2Mk1pDT"><img src="https://i.ibb.co/dp5wHdR/Screenshot-from-2022-04-07-11-25-59.png" alt="Screenshot-from-2022-04-07-11-25-59" border="0"></a>

Снова заходим и опять убеждемся, что все работает

<a href="https://ibb.co/h1HB1wm"><img src="https://i.ibb.co/rfMxfNw/Screenshot-from-2022-04-07-11-38-56.png" alt="Screenshot-from-2022-04-07-11-38-56" border="0"></a>
