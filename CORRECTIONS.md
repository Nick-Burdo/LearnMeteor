# Правки к курсу "DISCOVER METEOR"

[DISCOVER METEOR](http://ru.discovermeteor.com/)

## Сессия

В новых версиях `Meteor` cессия больше не поддерживается по умолчанию. Необходимо установить пакет:
```
meteor add session
```


## Добавление пользователей

Если возникает ошибка при установке пакета поддержки паролей
```
meteor add accounts-password
```

необходимо сначала установить пакет обертки `bcrypt`
```
meteor add npm-bcrypt
```
