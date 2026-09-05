# LinuxTeacher-Vagrant

Установлены на хостовую машину Ubuntu 24.04.

Гостевая система — ubuntu/22.04 из https://vagrant.elab.pro/downloads/.

**Домашнее задание:**

Цель домашнего задания:

Расширенная настройка дисков и сетей

Цель:

- научиться добавлять диски и настраивать сетевые соединения;

Убеждаемся что VirtualBox установлен:

<img width="754" height="77" alt="image" src="https://github.com/user-attachments/assets/4f6fc16f-9720-490a-ba8d-61ae80da53b4" />

Убеждаемся что установлен Vagrant:

<img width="758" height="81" alt="image" src="https://github.com/user-attachments/assets/97baafb5-1d29-443b-8f34-da8f85524e4b" />

Используется образ ubuntu/22.04

Настроил память ВМ: 2048 МБ.

В процессе разворачивания виртуальной машины будет происходить:

Добавление дисков:

3 -виртуальных диска размером 1 ГБ каждый.

Настройка сети:

Настройте проброс 80 порта с гостевой системы на порт 8084 хостовой системы. (порт 8080 занят)

Провижининг:

Напишите провижининг, который:

Форматирует добавленные диски в файловую систему ext4.

Создает точки монтирования /mnt/sdc1, /mnt/sdd1 /mnt/sde2.

Монтирует диски в указанные директории.

Добавляет записи в /etc/fstab для автоматического монтирования при загрузке.

-----

Был создан каталог ~./OTUS/vagrant/

<img width="561" height="140" alt="image" src="https://github.com/user-attachments/assets/96b01b90-c25e-479c-90f1-8767516e46b9" />

Так же дополнительно был создан каталог со скриптов для работы с дисковым пространством внутри ВМ:

<img width="561" height="140" alt="image" src="https://github.com/user-attachments/assets/fe9c40ac-4fe4-4aa2-9018-f2934597d572" />

Запускаю VM, работа команды записана в log:

<img width="621" height="93" alt="image" src="https://github.com/user-attachments/assets/77a28dfc-935b-48f0-b8e5-a9b228d28102" />




