# Домашнее задание к занятию «Система мониторинга Prometheus»" - `Мильдзихов Сергей`

Это задание для самостоятельной отработки навыков и не предполагает обратной связи от преподавателя. Его выполнение не влияет на завершение модуля. Но мы рекомендуем его выполнить, чтобы закрепить полученные знания.
### Цели задания

Научиться устанавливать Prometheus
Научиться устанавливать Node Exporter
Научиться подключать Node Exporter к серверу Prometheus
Научиться устанавливать Grafana и интегрировать с Prometheus
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

Установите Prometheus.



### Процесс выполнения

Выполняя задание, сверяйтесь с процессом, отражённым в записи лекции

Создайте пользователя prometheus

Скачайте prometheus и в соответствии с лекцией разместите файлы в целевые директории

Создайте сервис как показано на уроке

Проверьте что prometheus запускается, останавливается, перезапускается и отображает статус с помощью systemctl

### Требования к результатам
Прикрепите к файлу README.md скриншот systemctl status prometheus, где будет написано: prometheus.service — Prometheus Service Netology Lesson 9.4 — [Ваши ФИО]

### Решение
[1](111.png)


---

### Задание 2

Установите Node Exporter.

### Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.

Скачайте node exporter приведённый в презентации и в соответствии с лекцией разместите файлы в целевые директории

Создайте сервис для как показано на уроке

Проверьте что node exporter запускается, останавливается, перезапускается и отображает статус с помощью systemctl

### Требования к результатам

Прикрепите к файлу README.md скриншот systemctl status node-exporter, где будет написано: node-exporter.service — Node Exporter Netology Lesson 9.4 — [Ваши ФИО]




### Решение


---

### Задание 3

Подключите Node Exporter к серверу Prometheus.

### Процесс выполнения

Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.

Отредактируйте prometheus.yaml, добавив в массив таргетов установленный в задании 2 node exporter

Перезапустите prometheus

Проверьте что он запустился

### Требования к результатам

Прикрепите к файлу README.md скриншот конфигурации из интерфейса Prometheus вкладки Status > Configuration
Прикрепите к файлу README.md скриншот из интерфейса Prometheus вкладки Status > Targets, чтобы было видно минимум два эндпоинта


### Решение


