# Инструкция по работе с Git и удаленными репозиториями.

## Что такое Git?
***Git*** - это одна из реализаций распределенной системы контроля версий, поддерживающие как локальные, так и удаленные репозитории. Самая популярная реализация Git - это [Github](https://github/com)

## Подготовка репозитория
Для создания репозитория используеьтся команда *git init*. Для этого необходимо открыть в терминале папку с будущим репозиторием и там написать *git init*.

## Создание коммитов

## Выполнение коммита
Для того, чтобы выполнить коммит используется команда *git commit*. Для этого в терминале с папкой-репозиторием необходимо написать *git commit-m "<сообщение к коммиту>"*. Сщщбщение к клммиту ***ОБЯЗАТЕЛЬНО!!!***

## Добовление файла к коммиту
Для добовления файла к коммиту используется команда *git add*. Для этого втерминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Журнал изменений
Ддя просмотра истории коммитов используется команда *git log*. Для этого в терминале с папкой-репозиторием пишим *git log*. В журнале обязательно будут:
* Хэш(номер) коммита
* Дата и время коммита
* Автор коммита
* Текст сщщбщение к коммиту

## Перемещение между коммитами
Для перемещения между коммитами используется команда *git checkout*. Для этого в терминале с папкой репозиторием необходимо написать *git checkout <хэш коммита>*. Хэш коммита можно взять из истории коммитов, про которую было рассказано в предыдущем пункте.


## Ветки в Git

## Создание веток  
Для добовления новой ветки используется команда *git branch*. Для этого в терминале с папкой-репозиторием пишим *git branch <имя ветки>*. Название должно быть ***УНИКАЛЬНО***!

## Переключение между ветками
Для переключения между веток используется команда *git checkout*. Для этого втерминале с папкой-репозиторием необходимо написать *git checkout <имя ветки>*. Ветка обязательно должна существовать.

## Слияние веток
Для того, чтобы слить одну ветку в другую нужно вначале переключиться на ту ветку, с которой нужно слить изменения. Для слияния веток используется команда *git merge*. Для этого в терминале с папкой-репозиторием пишим *git merge <имя ветки>*.

## Разрешение конфликтов
Конфликты возникают при слиянии веток если в этих ветках одна и та же строка была изменена по-разному. Тогда получается, что Git не может сам решить какое из изменений нужно применить и он предлагает вручную решить эту ситуацию. Кофликт можно разрешить, создав новое сохранение для изменений и закоммитив его. Для просмотра кофликтующих файлов можно использовать команду *git status*, а с помощью команды *git log --merge* можно просмотреть журнал со списком конфликтов коммитов между ветками, для которых выполняется слияние.
Для того, чтобы слить одну ветку в другую нужно вначале переключиться на ту ветку, с которой нужно слить изменения. Для слияния веток используется команда *git merge*. Для этого в терминале с папкой-репозиторием пишим *git merge <имя ветки>*.

## Удаление веток
Для удаление веток используется команда *git branch -d*. Для этого в терминале с папкой репозиторием необходимо написать *git branch -d <имя ветки>*. Ветка, которую вы удаляете, не должна быть вашей текущей веткой, в которой вы работаете, иначе отобразится ошибка.
