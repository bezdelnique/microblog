# Описание проекта

Первая часть прохождения руководства по Flask от Miguel Grinberg.<br>
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

Вдумчиво вносил все изменения производимые в процессе реализации
* Chapter 1: Hello, World!
* Chapter 2: Templates
* Chapter 3: Web Forms
* Chapter 4: Database (this article)
* Chapter 5: User Logins
* Chapter 6: Profile Page and Avatars
* Chapter 7: Error Handling
* Chapter 8: Followers
* Chapter 9: Pagination
* Chapter 10: Email Support
* Chapter 11: Facelift
* Chapter 12: Dates and Times
* Chapter 13: I18n and L10n
* Chapter 14: Ajax

https://github.com/bezdelnique/microblog/commits/master


## Освоенные инструменты и библиотеки

* flask
* jinja2
* wtforms
* alembic
* sqlalchemy 
* click
* pybabel
* smtpd DebuggingServer

## Установка и запуск

```
git clone git@github.com:bezdelnique/microblog.git microblog
cd microblog
pip3 install -r requirements.txt
flask db upgrade
flask run
```
