## Задание: Настройка виртуальной инфраструктуры.

Для выполнения задания используйте дистрибутив [proxmox](https://www.pfsense.org/download/)

1. Установите гипервизор

2. Настройте хранилище для образов виртуальных машин (сравните разные ФС EXT4/XFS/BTRFS/ZFS/LVM и типы дисков RAW/Qcow2)

2. Создайте виртуальные изолированные сети

3. Создайте шаблоны для ОС linux и Windows (настройте использование гостевых утилит)

4. Создайте несколько клонов VM. Используйте sysprep для Windows и cloudinit для linux

5. Настройте сжатие образов виртуальных машин (на уровне стораджа)

6. Настройте вложенную виртуализацию.

7. Настройте вложенный кластер proxmox с работающей миграцией VM

8. Настройте резервное копирование

9. Настройте дедупликацию

10. Рассчитайте кол-во ресурсов гипервизора, для overcommit 3:1. При рассчете стораджа учитывайте сжатие

11. Оптимизируйте использование ресурсов с помощью KSM и Balooning

12. Используйте гипервизор для дальнейших практических работ