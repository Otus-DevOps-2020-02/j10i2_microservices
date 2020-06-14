# j10i2_microservices
j10i2 microservices repository

docker-3

# Выполнено ДЗ №16

 - [ ] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Разделен принцип работы с нашим приложением как с набором микросервисов
 - Уменьшен размер одного из образов
 - Сохоанена конфигурация базы данных
 - Настроен принцип работы с разными сетевыми элиасами (суть чтобы применился новый alias нужно изменить переменную окружения через  -e )_

## Как запустить проект:
 - docker build -t ....

## Как проверить работоспособность:
 - Например, перейти по ссылке http://35.241.222.46:9292

## PR checklist
 - [ ] Выставил label с номером домашнего задания
 - [ ] Выставил label с темой домашнего задания

# j10i2_microservices


# Выполнено ДЗ №18

 - [ ] Основное ДЗ


## В процессе сделано:
 - Рассмотрена работа с сетями
 - Построен docker-compose для микросервисов



## PR checklist
 - [ ] Выставил label с номером домашнего задания
 - [ ] Выставил label с темой домашнего задания


 Ссылка на образы докерхаб - https://hub.docker.com/u/j10i2
=======
Выполнено ДЗ №15 (docker-2)
[*] Основное ДЗ
[*] Задание со *
В процессе сделано:
Рассмотрен вывод докера и создан докер-контейнер
Поднято удаленное окружение с докером и приложением
Рассмотрена разница в файле docker.log между выводами
Настроено окружение infra с докер-образом
Добавлен удаленный репозиторий
Как запустить проект:
docker run --name reddit -d -p 9292:9292 j10i2/otus-reddit:1.0
http://35.241.222.46:9292
Как проверить работоспособность:
http://35.241.222.46:9292
PR checklist
 Выставил label с номером домашнего задания
 Выставил label с темой домашнего задания

