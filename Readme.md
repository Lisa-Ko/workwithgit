# Инструкция по работе с Git

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

## Слияние веток и разрешение конфликтов

## Удаление веток
Для удаление веток используется команда *git branch -d*. Для этого в терминале с папкой репозиторием необходимо написать *git branch -d <имя ветки>*. Ветка, которую вы удаляете, не должна быть вашей текущей веткой, в которой вы работаете, иначе отобразится ошибка.