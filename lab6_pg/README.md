## Наша цель- посторить коммунизм, то есть настроить репликацию данных в PostgreSQL

<a href="https://ibb.co/thxcPRX"><img src="https://i.ibb.co/pPRZrqy/our-meme-template-fo6o2.jpg" alt="our-meme-template-fo6o2" border="0"></a>

По стандарту сначала поднимаем наши сервера:

```
vagrant up
```

А далее запускаем плэйбук:

```
ansible-playbook pgsql.yml
```

Теперь все данные будут храниться в нашей базе данных, а изменения автоматически синхронизироваться на другие.
PostgreSQL-сервер создает пустой файл standby.signal, который говорит о том, что сервер-реплика.

<a href="https://ibb.co/WyHBs6N"><img src="https://i.ibb.co/0MnYQcp/Screenshot-from-2022-04-13-13-53-35.png" alt="Screenshot-from-2022-04-13-13-53-35" border="0"></a>

В нашем случае это сервер pgsql2.

## Теперь мы готовы строить коммунизм и прославлять Советский Союз

<a href="https://imgbb.com/"><img src="https://i.ibb.co/RvpyHVn/0bjzwq-P-7g.jpg" alt="0bjzwq-P-7g" border="0"></a>
