## Задание: Windows Server. Настройка серверных ролей AD, GPO, FS.

1. Поднять AD
    1. Создать структуру домена
    1. Создать УЗ юзеров
    1. Создать УЗ для сервисов
    1. Настроить сайты, репликацию
    1. Добавить кастомное поле через схему.
    1. Создать второй домен и доверие между ними
1. Поднять DHCP, настроить регистрацию не доменных клиентов в DNS
1. Настроить тестовую зону DNS, например, test.yandex.ru, но, чтобы yandex.ru и прочие сервисы работали.
1. Создать GPO:
    1. Создает кастомный каталог у пользователей и задает права группе AD
    1. Ожидать инициализации сети при загрузке и входе в систему
    1. запретить запуск Диспетчера задач
    1. настроить перемещаемые профили
    1. настроить AppLocker
    1. Настроить блокировку компьютера при простое
    1. Настроить IE
    1. Настроить удаленный доступ
    1. Блокирование наследования групповой политики
    1. Установить системные компоненты средствами групповой политики
    1. Создать ветку в реестре
1. Настроить файловый сервер
    1. DFS дерево
    1. Скрыть папки от пользователей у которых нет прав
    1. Раздать права доступа по доменным группам
    1. Раздать права пользователю из другого домена
    1. Настроить бэкап 

### Windows службы кластеризации
1. Настройка службы кластеризации (поднять кластер из 2 нод)
2. Настройка ролей
    1. Настроить роль файлового сервера
    1. Настроить роль для DNS записи IIS сервера
4. SMB 3 протокол (протестировать/включить шифрование)
5. Настройка IIS кластера
6. Изучить Кластерные FS
7. Настроить растянутый файловый кластер
8. Настроить Hyper V кластер