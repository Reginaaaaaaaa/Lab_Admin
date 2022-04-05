## Плэйбук для балансировки двух страниц (web1 и  web2)

Для начала, нам необходим образ  CentOS7.

Для старта нашей виртуальной машины используйте команду:

'''

vagrant up

'''

Далее команда для запуска плэйбука:

'''

ansible-playbook nginx

'''

## Последний рубеж

Переходим на кастомную страницу по ip http://192.168.11.113 и наслаждаемся тем, какие мы молодцы!

Наглядная работа:

<a href="https://ibb.co/bHMP9GG"><img src="https://i.ibb.co/k3sxCPP/Screenshot-from-2022-04-05-11-05-15.png" alt="Screenshot-from-2022-04-05-11-05-15" border="0"></a>

Обновляем страницу и наблюдаем, как они меняются:

<a href="https://ibb.co/S0z49Ws"><img src="https://i.ibb.co/Gkq4bBx/Screenshot-from-2022-04-05-11-04-43.png" alt="Screenshot-from-2022-04-05-11-04-43" border="0"></a>
