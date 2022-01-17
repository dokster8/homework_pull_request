# Инструкция по работе с Git
![error](photo.png)
## Начало работы с репозиторием
* создать репозиторий:
>git init

* Задать имя пользователя и почту:
>git config --global user.name "name"

>git config --global user.email "example@mail.ru"
## Добавление файлов в репозиторий
* Добавить "file_name" для отслеживания:
>git add fike_name

* Зафиксировать файл, добавленный для отслеживания и оставить комментарий:
>git commit -m "write message"

## Отслеживание состояние репозитория
* Показать измененные файлы и файлы готовые для коммита:
>git status

* Показать все коммиты:
>git log

* Показать разницу, между текущей и зафиксированной версией:
>git diff
## Переход между коммитами
* Переход к коммиту по его коду "com_code" (можно посмотреть в git log):
> git checkout com_code

Вернуться в актуальное состояние кода:
>git checkout master

## Ветки в git
* Посмотреть все ветки:
>git branch
* Для создания ветки branch_name:
>git branch branch_name
* Переместиться к ветке branch_name
>git checkout branch_name