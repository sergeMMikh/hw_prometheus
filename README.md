# Домашнее задание к занятию «Prometheus» - Михалёв Сергей
---

### Задание 1*
Установите Prometheus.

#### Процесс выполнения
1. Выполняя задание, сверяйтесь с процессом, отражённым в записи лекции
2. Создайте пользователя prometheus
3. Скачайте prometheus и в соответствии с лекцией разместите файлы в целевые директории
4. Создайте сервис как показано на уроке
5. Проверьте что prometheus запускается, останавливается, перезапускается и отображает статус с помощью systemctl

#### Pезультат
- скриншот systemctl status prometheus, где написано: prometheus.service — Prometheus Service Netology Lesson 9.4 — [ФИО]
  * <img src="images/Task_1_1.jpg" alt="Task_1_1" width="500" height="auto">

---

### Задание 2*
Установите Node Exporter.

#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
3. Скачайте node exporter приведённый в презентации и в соответствии с лекцией разместите файлы в целевые директории
4. Создайте сервис для как показано на уроке
5. Проверьте что node exporter запускается, останавливается, перезапускается и отображает статус с помощью systemctl

#### Требования к результату
- скриншот systemctl status node-exporter, где будет написано: node-exporter.service — Node Exporter Netology Lesson 9.4 — [ФИО]
  * <img src="images/Task_2_1.jpg" alt="Task_1_1" width="500" height="auto">

---

### Задание 3*
Подключите Node Exporter к серверу Prometheus.

#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Отредактируйте prometheus.yaml, добавив в массив таргетов установленный в задании 2 node exporter
3. Перезапустите prometheus
4. Проверьте что он запустился

#### Требования к результату
- скриншот конфигурации из интерфейса Prometheus вкладки Status > Configuration
  * <img src="images/Task_3_1.jpg" alt="Task_3_1" width="500" height="auto">
- скриншот из интерфейса Prometheus вкладки Status > Targets, чтобы было видно минимум два эндпоинта
  * <img src="images/Task_3_2.jpg" alt="Task_3_2" width="500" height="auto">

---

### Задание 4*
Установите Grafana.

#### Требования к результату
- скриншот левого нижнего угла интерфейса, чтобы при наведении на иконку пользователя были видны ФИО
  * <img src="images/Task_4_1.jpg" alt="Task_4_1" width="300" height="auto">

---
