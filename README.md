# My Roadmap for Sysadmin / DevOPS / SRE


![My Roadmap for Sysadmin / DevOPS / SRE](./roadmap.png)

Данный репозиторий содержит Roadmap для обучения по следующим темам:

* Базовая информация по серверному оборудованию
* Работа с системами виртуализации
* Работа с сетями
* Системное администрирование Windows / Linux
* DevOPS практики и инструменты
* Автоматизация и написание скриптов на Powershell / Bash / Python
* Работа с системами мониторинга
* Работа с системами резервного копирования

Гайд в разработке..

1) **Железо и серверное оборудование**
   1. Устройство ПК
      1. [Какие бывают CPU и архитектуры](https://ru.wikipedia.org/wiki/%D0%A6%D0%B5%D0%BD%D1%82%D1%80%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9_%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D1%80#:~:text=%D0%9F%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D1%80%D1%8B%20Intel%3A%208086%2C%2080286%2C,%D0%B4%D0%BB%D1%8F%20%D0%B2%D1%81%D1%82%D1%80%D0%B0%D0%B8%D0%B2%D0%B0%D0%B5%D0%BC%D0%BE%D0%B9%20%D1%82%D0%B5%D1%85%D0%BD%D0%B8%D0%BA%D0%B8\)%20%D0%B8%20%D0%B4%D1%80.)
      1. Что такое [чипсет](https://ru.wikipedia.org/wiki/%D0%A7%D0%B8%D0%BF%D1%81%D0%B5%D1%82)? [Сокет](https://ru.wikipedia.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D1%80%D0%B0%D0%B7%D1%8A%D1%91%D0%BC%D0%BE%D0%B2_%D0%BC%D0%B8%D0%BA%D1%80%D0%BE%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D1%80%D0%BE%D0%B2)? 
      1. [Какая бывает RAM](https://coderlessons.com/tutorials/akademicheskii/osnovy-operatsionnykh-sistem/5-razlichnye-tipy-operativnoi-pamiati)? [Каналы](https://ru.wikipedia.org/wiki/%D0%9C%D0%BD%D0%BE%D0%B3%D0%BE%D0%BA%D0%B0%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0_%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D0%B8) и [тд](https://ru.wikipedia.org/wiki/%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%BE%D0%B2%D0%B0%D1%8F_%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C)
      1. Диагностика неисправностей
      1. Настройка, установка ОС
      1. [BIOS](https://ru.wikipedia.org/wiki/BIOS#:~:text=BIOS%20\(%2F%CB%88ba%C9%AA%C9%92,%D0%B8%20%D0%BF%D0%BE%D0%B4%D0%BA%D0%BB%D1%8E%D1%87%D1%91%D0%BD%D0%BD%D1%8B%D0%BC%D0%B8%20%D0%BA%20%D0%BD%D0%B5%D0%BC%D1%83%20%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%B0%D0%BC%D0%B8.) / [EFI](https://ru.wikipedia.org/wiki/Extensible_Firmware_Interface) [отличия](https://habr.com/ru/post/185492/#:~:text=UEFI%20\(Unified%20Extensible%20Firmware%20Interface,%D0%BD%D0%B0%20x86%2C%20x64%20%D0%B8%20ARM.), зачем нужны? 
   1. Серверное оборудование
      1. [Спецификации](https://www.dell.com/en-us/work/shop/servers-storage-and-networking/poweredge-r640-rack-server/spd/poweredge-r640/pe_r640_12232_vi_vp), пример конфигурации
      1. Удаленное управление (IMM, [IDRAC](https://en.wikipedia.org/wiki/Dell_DRAC), ILO), обновление прошивок
      1. Резервирование оборудования (БП. Память. сеть)
      1. [Установка в стойку](https://wtlan.ru/presscenter/news/detail.php?ID=1795), охлаждение, питание
      1. Конфигурация дисковой подсистемы
         1. [SATA](https://ru.wikipedia.org/wiki/SATA)/[SAS](https://ru.wikipedia.org/wiki/Serial_Attached_SCSI)/[M2](https://ru.wikipedia.org/wiki/M.2) и тд
         1. HDD ([10k](https://www.xcom-shop.ru/catalog/kompyuternye_komplektyyuschie/hdd_zhestkie_diski/hdd_3525_sas_server/), 7200, [черепичные](https://www.nix.ru/computer_hardware_news/hardware_news_viewer.html?id=190645) [диски](https://www.hardwareluxx.ru/index.php/artikel/hardware/storage/49812-cmr-protiv-smr-vyvodim-proizvoditelej-hdd-na-chistuyu-vodu.html) и тд)
         1. Дисковые полки
            1. [ISCSI](https://ru.wikipedia.org/wiki/ISCSI#:~:text=iSCSI%20%D0%BE%D0%BF%D0%B8%D1%81%D1%8B%D0%B2%D0%B0%D0%B5%D1%82%3A,%C2%AB%D1%80%D0%BE%D0%B4%D0%BD%D0%BE%D0%B9%C2%BB%20TCP%2FIP.)
            1. [FC](https://ru.wikipedia.org/wiki/Fibre_Channel#:~:text=fibre%20channel%20%E2%80%94%20%D0%B2%D0%BE%D0%BB%D0%BE%D0%BA%D0%BE%D0%BD%D0%BD%D1%8B%D0%B9%20%D0%BA%D0%B0%D0%BD%D0%B0%D0%BB\)%20%E2%80%94,%D0%BF%D1%80%D0%BE%D1%82%D0%BE%D0%BA%D0%BE%D0%BB%D0%BE%D0%B2%20%D0%B4%D0%BB%D1%8F%20%D0%B2%D1%8B%D1%81%D0%BE%D0%BA%D0%BE%D1%81%D0%BA%D0%BE%D1%80%D0%BE%D1%81%D1%82%D0%BD%D0%BE%D0%B9%20%D0%BF%D0%B5%D1%80%D0%B5%D0%B4%D0%B0%D1%87%D0%B8%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.)
               1. [Сеть, коммутаторы, оптика](http://blog.korphome.ru/2016/12/21/brocade-san/)
               1. Подключение напрямую.
            1. [SAS](https://ru.wikipedia.org/wiki/JBOD)
            1. Плюсы и минусы технологий.
         1. [RAID](https://ru.wikipedia.org/wiki/RAID) какие виды бывают
            1. [Контроллеры RAID](https://habr.com/ru/company/pc-administrator/blog/304798/) (кеш и тд. [Режимы записи](http://www.gilev.info/2018/09/raid-raid.html))
      1. [Сбор логов, диагностика](https://support.lenovo.com/ru/en/solutions/ht508597-how-to-collect-service-logs-on-a-local-system-using-dynamic-system-analysis-dsa-preboot-edition)






1) **ОС Windows Server**
   1. [Установка](https://computingforgeeks.com/install-windows-server-2019/) ([драйвера](https://woshub.com/integrate-drivers-to-windows-install-media/), оптимизации и тд)
   1. Кастомизация образов ([DISM](https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/mount-and-modify-a-windows-image-using-dism?view=windows-11))
   1. [Troubleshooting](https://learn.microsoft.com/en-us/troubleshoot/windows-server/welcome-windows-server)
   1. [Реестр](https://learn.microsoft.com/en-us/troubleshoot/windows-server/performance/windows-registry-advanced-users) (общая информация)
   1. Удаленное управление
      1. [WMI](https://habr.com/ru/articles/70806/)
      1. [Powershell](https://learn.microsoft.com/en-us/powershell/scripting/learn/ps101/01-getting-started?view=powershell-7.3)
      1. [winRM](https://winitpro.ru/index.php/2012/01/31/kak-aktivirovat-windows-remote-management-s-pomoshhyu-gruppovoj-politiki/)
      1. [admin center](https://learn.microsoft.com/en-us/windows-server/manage/windows-admin-center/use/get-started?tabs=add-one)
   1. Файловые системы (FAT, NTFS, ReFS), [размер кластера фс](https://www.white-windows.ru/chto-takoe-razmer-klastera-zhyostkogo-diska-i-kak-ego-izmenit-bez-formatirovaniya-razdela/), [дефрагментация](https://ru.wikipedia.org/wiki/%D0%94%D0%B5%D1%84%D1%80%D0%B0%D0%B3%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F_%D0%B4%D0%B8%D1%81%D0%BA%D0%B0)
   1. Серверные роли
      1. [Файловый сервер](https://www.server-world.info/en/note?os=Windows_Server_2019&p=smb&f=1)
      1. [DNS](https://www.server-world.info/en/note?os=Windows_Server_2019&p=dns&f=1)/[DHCP](https://www.server-world.info/en/note?os=Windows_Server_2019&p=dhcp&f=1)
      1. [AD/DC](https://www.server-world.info/en/note?os=Windows_Server_2019&p=active_directory&f=1)
      1. [CA](https://thesecmaster.com/step-by-step-procedure-to-set-up-a-standalone-root-ca-on-windows-server/)
      1. IIS
      1. KMS
      1. Remote Access
      1. Hyper-V
      1. WSUS
      1. Deployment
   1. Серверные фичи
      1. Branch Cache
      1. Failover Clustering
      1. I/O qos
      1. IPAM
      1. MSMQ
      1. Multipath IO
      1. SMTP 
      1. Backup
   1. Sysprep (Подготовка образа к развертыванию)





1) **Сеть и связанные службы**
   1. Какие сети бывают?
   1. Маска подсети
   1. Модель OSI
   1. Роутинг
      1. Статика
      1. Динамический роутинг
         1. Ergp
         1. OSPF
         1. BGB
      1. Сетевые модели, ядро сети, отказоустойчивость
   1. VLAN
   1. Тунели
   1. NAT
   1. ACL
   1. NTP
   1. VRRP
   1. Тиминг 
   1. DHCP сервер (как работает, helper)
   1. DNS сервер
   1. Firewall
   1. QOS
   1. IPSEC



1) **Домен, авторизация, аутентификация, управление**
   1. Что такое AD и зачем нужно?
   1. DHCP и AD
   1. DNS и AD
      1. Домен и внешняя зона DNS
   1. GPO, что такое и зачем?
   1. Роли AD
   1. Аудит
   1. Домены и доверие? 
   1. LDAP
   1. NTP
   1. Схема, структура, атрибуты 
   1. Группы (глобальные, локальные, универсальные)
   1. Типы УЗ
   1. Логирование \ troubleshooting
   1. Репликация, сайты. 
   1. Kerberos
   1. Восстановление DC
   1. Корзина AD
   1. Миграция домена
   1. Переименование домена (UPN, полное переименование)
   1. AD и CA
   1. SPN
   1. DFS







1) **ОС Linux**
   1. Установка и настройка Linux
      1. [Отличия deb based от rpm based](https://linuxgenie.net/difference-between-linux-deb-vs-rpm/)
      1. Установка Linux
         1. [ubuntu](https://ubuntu.com/server/docs/installation)
         1. [RHEL based](https://docs.centos.org/en-US/centos/install-guide/Simple_Installation/)
      1. Настройка основных параметров системы
         1. [изменить hostname](https://www.tecmint.com/set-change-hostname-in-centos-7/)
         1. [изменить пароль root](https://www.cyberciti.biz/faq/how-to-change-root-password-on-centos-linux/)
         1. [изменить часовой пояс](https://linuxize.com/post/how-to-set-or-change-timezone-on-centos-7/)
         1. [настроить сеть](https://phoenixnap.com/kb/configure-centos-network-settings)
      1. Работа в командной строке
         1. [Основные команды Linux](https://selectel.ru/blog/basic-linux-commands/)   
         1. [Управление файлами и папками](https://selectel.ru/blog/tutorials/files-and-directories-in-linux/)     
         1. [Редактирование текстовых файлов](https://www.hostwinds.ru/tutorials/how-to-edit-files-from-linux-shell)     
         1. [Настройка прав доступа к файлам](https://habr.com/ru/articles/469667/)     
      1. Пакетный менеджер (Установка и удаление программ/Обновление системы/Поиск и установка пакетов)
         1. [apt](https://linuxize.com/post/how-to-use-apt-command/)  
         1. [yum](https://access.redhat.com/solutions/9934)  
         1. [dnf](https://docs.fedoraproject.org/en-US/quick-docs/dnf/) 
         1. [zypper](https://documentation.suse.com/sles/12-SP5/html/SLES-all/cha-sw-cl.html)  
      1. Работа с пользователями и группами
         1. [Создание и управление пользователями](https://www.cyberciti.biz/faq/create-a-new-user-account-in-centos-7-8-linux/)  
         1. Назначение прав доступа пользователю
            1. [sudo](https://linuxize.com/post/how-to-add-user-to-sudoers-in-centos/) 
            1. [file permissions](https://linuxhint.com/give-user-folder-permission-linux/)
         1. [Создание и управление группами](https://linuxize.com/post/how-to-create-groups-in-linux/)                          

      1. Системный мониторинг и администрирование
        1. [Работа с процессами](https://www.opennet.ru/docs/RUS/lnx_process/process2.html) 
            1. [как работают процессы](https://habr.com/ru/articles/423049/)
        1. [Работа с сервисами и демонами](https://habr.com/ru/companies/slurm/articles/255845/) 
        1. Управление дисками и разделами
            1. [общая информация о партициях](https://docs.centos.org/en-US/centos/install-guide/Partitions-x86/)        
            1. [создать партиции](https://docs.centos.org/en-US/centos/install-guide/Partitions-x86/) 
                1. [parted](https://www.thegeekdiary.com/how-to-create-a-partition-using-parted-command/)   
                1. [fdisk](https://www.digitalocean.com/community/tutorials/create-a-partition-in-linux)
            1. [LVM](https://linuxhint.com/install_lvm_centos/)
      1. Сетевая настройка
         1. [настроить сеть](https://phoenixnap.com/kb/configure-centos-network-settings)                        
         1. [Настройка DNS](https://bitlaunch.io/blog/how-to-edit-dns-servers-in-centos/)      
         1. Фаерволл и безопасность сети
            1. [firewalld](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-using-firewalld-on-centos-8)
            1. [ufw](https://phoenixnap.com/kb/configure-firewall-with-ufw-on-ubuntu)
      1. Автоматизация задач
         1. [Создание скриптов на языке командной строки](https://www.freecodecamp.org/news/bash-scripting-tutorial-linux-shell-script-and-command-line-for-beginners/)                        
         1. [Планирование задач с помощью Cron](https://opensource.com/article/17/11/how-use-cron-linux) 
         1. [Использование утилиты "at" для задач по расписанию](https://redos.red-soft.ru/base/manual/utilites/at-atd/) 
         1. [Использование systemd-timers для задач по расписанию](https://opensource.com/article/20/7/systemd-timers) 

      1. Защита системы
         1. [использование ssh ключей](https://www.vultr.com/docs/centos-8-setting-up-access-with-ssh/)                        
         1. [отключение root](https://www.tecmint.com/disable-root-login-in-linux/) 
         1. [SElinux](https://wiki.centos.org/HowTos(2f)SELinux.html) 
         1. [APParmor](https://ubuntu.com/server/docs/security-apparmor) 



1) **Виртуализация**
   1. Зачем нужна? 
   1. Какого типа бывают гипервизоры
   1. Как считать и делить ресурсы?
      1. CPU Overcommit
      1. Память, KSM, Balooning? 
      1. Storage. Сжатие, шифрование, дедупликация, форматы дисков
   1. Как выбрать платформу?
   1. Производительность, на что смотреть и как диагностировать?
   1. Снапшоты
   1. Шаблонизирование, как делать правильно?
   1. Бэкапы
   1. Оптимизация гостевых ОС
   1. Безопасность
   1. Вложенная виртуализация
   1. SRVIO
   1. PCI Passtrough
   1. USBIP
   1. WAL
   1. Перенос VM между гипервизорами.

1) **Веб. IIS / nginx / haproxy**
   1. Протоколы HTTP \ [HTTPS](https://www.ssllabs.com/ssltest/analyze.html?d=ya.ru&latest)
   1. Настройка IIS / nginx / haproxy
   1. Кластеризация IIS
   1. Типы редиректов
   1. Реверс прокси на IIS / nginx / haproxy
   1. CGI
   1. Аутентификация (basic/kerberos/etc)






1) **Автоматизация**
   1. Powershell
      1. Командлеты
      1. IF , for , try/catch
      1. Массивы 
      1. Фильтрация данных
      1. Функции
      1. Параллельное выполнение
      1. Работа с REST API
      1. Импорт/экспорт данных
      1. Удаленное управление 

   1. Bash
      1. Основные команды, работа с pipe
      1. IF , for , обработка ошибок, работа с вводом/выводом
      1. Массивы 
      1. Фильтрация данных
      1. Функции
      1. Параллельное выполнение
      1. Работа с REST API
      1. Импорт/экспорт данных
      1. Удаленное управление через ssh

   1. Python
      1. Основы языка Python (синтаксис, переменные, типы данных, операторы)
      1. Условные выражения (if, elif, else)
      1. Циклы (for, while)
      1. Обработка исключений (try, except)
      1. Списки / словари и тд
      1. Фильтрация данных (использование условий и функций фильтрации)
      1. Функции и процедуры
      1. Многопоточное программирование (использование потоков или модуля threading)
      1. Работа с REST API (использование модуля requests)
      1. Импорт и экспорт данных (работа с различными форматами данных, такими как CSV, JSON, XML)
      1. Удаленное управление (использование модуля paramiko для SSH или создание собственного протокола связи)

1) **Мониторинг**
   1. Системные метрики
      1. CPU
      1. RAM
      1. HDD
      1. IO
      1. NET
   1. Системы мониторинга
      1. Grafana
      1. Zabbix
      1. Prom
      1. Telegraf
   1. Бизнес мониторинг








1) **DevOPS**
   1. [GIT](https://git-scm.com/docs/gittutorial)
      1. IDE (VC Code, Pycharm)
   1. CI/CD системы
      1. Github \ Bitbucket
      1. Gitlab
      1. Teamcity
   1. CI/CD системы (Сборка и упаковка)
      1. [Gitlab](https://docs.gitlab.com/ee/ci/quick_start/)   
      1. [Gitlab docker](https://docs.gitlab.com/ee/ci/docker/using_docker_build.html)
    1. Контейнеризация (Docker, Kubernetes)
       1. [Docker](https://docker-curriculum.com/)
       1. [Docker Compose](https://docs.docker.com/compose/gettingstarted/)
       1. [Kubernetes](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
    1. Системы управления конфигурациями
       1. [Ansible](https://docs.ansible.com/ansible/latest/getting_started/index.html)
       1. [Puppet](https://www.digitalocean.com/community/tutorial-series/how-to-use-puppet-to-manage-your-servers-2)
       1. [DSC](https://learn.microsoft.com/en-us/powershell/dsc/getting-started/wingettingstarted?view=dsc-1.1)
       1. [GPO](https://www.pcwdld.com/group-policy-management)
    1. Мониторинг и логирование
       1. [ELK](https://logz.io/learn/complete-guide-elk-stack/#installing-elk)
       1. [Prometheus](https://prometheus.io/docs/prometheus/latest/getting_started/)
       1. [Prometheus Alerts](https://prometheus.io/docs/alerting/latest/configuration/)
       1. [Grafana](https://grafana.com/tutorials/grafana-fundamentals/)
    1. IAC
    1. SEC    
       1. [Ansible vault](https://www.digitalocean.com/community/tutorials/how-to-use-vault-to-protect-sensitive-ansible-data)    
       1. [hashicorp vault](https://www.digitalocean.com/community/tutorials/how-to-securely-manage-secrets-with-hashicorp-vault-on-ubuntu-20-04)    
       1. [Ansible use hashicorp vault](https://elatov.github.io/2022/01/using-hashicorp-vault-with-ansible/)







1) **Бэкапы**
   1. Типы
      1. Полный
      1. Диф
      1. Инкремент 
   1. Что бэкапить? 
      1. ОС
      1. БД
      1. VM
      1. Файлы
   1. Репликация и тд
   1. Как правильно бэкапить? 
   1. Куда бэкапить? 
      1. Лента
      1. Хранилище
         1. Сетевое
         1. Локальное
         1. Распределенное
         1. Съемный носитель
            1. Картридж
            1. Диски
            1. HDD
   1. Софт
      1. Bacula
      1. Borg
      1. Veeam
      1. Acronis
      1. Arcserve
      1. Вендорские встроенные решения
         1. VMware свои решения (VM, файлы, БД)
         1. MS (БД, VM, ОС, файлы)
         1. IBM\DELL\HP
      1. Самописные решения
         1. Скрипты
         1. TAR
         1. 7zip 
         1. Клонирование образов
            1. Clonzilla
            1. Gparted
            1. Acronis
      1. Бэкап в облако
         1. Шифрование бэкапов
      1. Восстановление данных если нет бэкапа!


1) Инвентаризация 





