# yii1_spa_apachelogs


## Тестовое задание следующее

Используя на backend Yii1, реализовать SPA приложение, которое является агрегатором данных из access илогов apache с сохранением в БД.
Разбор файлов должен выполняться консольной командой Yii.

В приложении реализовать такие функции:

- авторизация (пользователи в БД)

- просмотр данных сохраненных в БД (группировка по IP, по дате, выборка по промежутку дат)

- API для получения данных в виде JSON (смысл тот же: получение данных по временному промежутку, возможность группировать/фильтровать по IP)

- конфигурация через файл настроек (где лежат логи, маска файлов, и все, что Вам потребуется для настройки приложения)

- на фронте использовать vue.js

Для исполнения интерфейса использовать bootstrap

СУБД: mysql

код задания нужно выложить в репозиторий на github\gitlab\bitbucket

В репозитории должна содержаться инструкция по запуску.
Достаточно распарсить один вид логов.
