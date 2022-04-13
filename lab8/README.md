# Patroni
Создаем отказоустойчивый кластер ДБ с помощью Consul и Patroni

## Installation

Разворачиваем вируальные машины, не забываем поменять путь Vagrantfile к Вашему SSH ключу

```bash
vagrant up
```

После поднятия машин запускаем плейбук по Consul для трех машин

```bash
ansible-playbook consul.play
```

Не обращаем внимания на hashicorp они закрыли доступ из России

Теперь запускаем плейбук для Patroni и vip-manager

```bash
ansible-playbook clients.yml
```

Для того чтобы vip-manager заработал нужно сделать switchover для смены лидера

```bash
patronictl -c /opt/app/patroni/etc/postgres.yml switchover
```
Смотрим через 

```bash
ip a
```
что наш адрес поднялся
