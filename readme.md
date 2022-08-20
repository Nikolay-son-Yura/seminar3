# Инструкция по работе с Git

## Что такое *Git*?
Git - одна из реализаций распределенных систем контроля версий,позволяющая организовать версионность, как локально,так и на удаленом сервере.Самая популярная платфоорма, реализующая *Git*. - [GitHub](http://github.com)

## Подготовка репозитория
Для создания в папке репозитория необходимо открыть эту папку в терминале и написать команду *git init* после чего в этой папке создасться скрытая папка *git* ,и таким образом папка станет репозиторием

## Создание коммитов

### Просмотр состояния репозитория
Для просмотра состояния репозитория используется команда *git status*. В терминале с открытой папкой-репозиторием необходимо написать команду *git status*. В результате можно увидеть следующие выводы
1. On branch *** noting to commit - это значит нет активных изменений
2. Untracked file - это значит,что имеются файлы, не отслеживаемые системы контроля версий
...

### Добавление файла к коммиту
Для того ,чтобы добавить файл к *сохранению* ,необходимо использовать команду *git add* . в терминале с открытой папкой-репозиторием необходимо написать *git add <название файла>*, и этот файл добавится к "сохранению"

### Создание фиксации
Для создания фиксации используется команда *git commit*. Для этого в терминале с папкой-репозиторием необходимо написать команду *git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**

## Журнал изменений
Для просмотра истории изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git log*, и Вы увидете список всех коммитов в этой ветке с описанием: имени, электронной почты, сообщением к коммиту и номером коммита

## Перемещение между коммитами
Для перемещения между коммитами используется команда *git checkout*. Для этого в терминале с папкой-репозиторием необходимо написать *git checkout<номер коммита>*. Номер коммита берется из журнала изменения ветки.

## Ветки в Git
Для создания новой ветки используется команда *git branch*. Для этого в терминале с папкой-репозиторием необходимо написать *git branch <название ветки>*. Создастся новая ветка с введеным названием. Исходная ветка всегда называется **master**

## Слияние веток и решение конфликтов

## Удаление веток