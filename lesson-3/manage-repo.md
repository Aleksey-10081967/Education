### Пакетные менеджеры

Полезные команды при работе с пакетными менеджерами apt/yum, которые могут пригодиться:

    apt remove – удалить пакет без измененных вами конфигов.
    apt purge – полностью удалить пакет, вместе со всеми его конфигурационными файлами;
    apt autoremove – очистить ненужные пакеты;
    apt autoclean – очистка кэша пакетов;
    apt upgrade – обновить пакет до актуальной версии, если пакет не указан будет обновлено всё.
    apt list выводит список доступных пакетов, а apt list --installed - установленных
    apt search cowsay – поиск пакетов с именем, которое включает ключевое слово “cowsay”;
    apt show cowsay – посмотреть информацию о пакете с именем “cowsay”;;
    apt edit-sources – открыть с настройками репозиториев в текстовом редакторе.
    apt build-dep – установить зависимости необходимые для сборки выбранного пакета;
    apt-cache depends - посмотреть зависимые пакеты.

Для yum:

Установить пакет: 

      yum install figlet 

Удалить пакет: 

      yum remove figlet 

Переустановить пакет: 

      yum reinstall figlet 

Найти пакет в репозиториях: 

      yum search figlet 

Отобразить информацию о пакете: 

      yum info figlet 

Обновить установленные пакеты: 

      yum update 

Обновить конкретный установленный пакет: 

      yum update figlet 

Обновить пакет до определенной версии:

      yum update-to

Показать историю: 

    yum history 

Вывести список включенных репозиториев: 

     yum repolist 

Найти пакет, который предоставляет файл (например, /usr/bin/figlet):

     yum provides "*bin/figlet" 

Очистить кэш: 

     yum clean all

 