# Менеджер заметок

## Инструкция по запуску приложения

Перед запуском необходимо установить [GIT](https://git-scm.com/download/win), а так же библиотеку pip.
1. Клонируем репозиторий (или определенную ветку) и заходим в папку:
```
$ git clone --branch master https://github.com/Dudhen/SkyEngTest.git
$ cd SkyEngTest
```
2. Загружаем все необходимые библиотеки:
```
$ pip install -r requirements.txt
```
3. Запускаем приложение локально:
```
$ python manage.py runserver
```
4. Приложение доступно по адресу http://127.0.0.1:8000/note/

5. Для доступа в административную панель необходимо создать суперпользователя
```
$ python manage.py createsuperuser
```
Панель администратора приложения доступно по адресу http://127.0.0.1:8000/admin/

## Внесение изменений в исходный код

### GIT
 
1. Для определения ветки, в которой мы находимся:
```
$ git branch
```
2. Для просмотра изменений, внесенных пользователем:
```
$ git status
```
3. Для сохранения изменений в исходном коде используются следующие команды:
```
$ git add .
$ git commit -m "Краткое описание изменений"
```
4. Для отправки изменений из локального репозитория в удаленный:
```
$ git push origin <название ветки>
```
5. Для получения данных из удаленного репозитория в локальный:
```
$ git pull origin <название ветки>
```
Дополнительная информация по [GIT на русском языке](https://git-scm.com/book/ru/v2)
