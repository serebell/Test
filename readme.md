# Инструкция для работы с Git и удаленными репозиториями 

## Что такое Git?
Git — это система контроля версий (VCS), которая позволяет отслеживать и фиксировать изменения в коде: вы можете восстановить код в случае сбоя или откатить до более ранних версий

## Как Git работает? 

Git помогает вернуть файлы в исходное состояние и видеть изменения, внесённые в определённый период. Разработчик выполняет разные команды (например, commit, push), а все изменения синхронизируются с центральным репозиторием. Git — это система контроля версий, а GitHub — онлайн-сервис, по сути социальная сеть.

## Список команд, необходимых в работе

**git int** - инициализация репозитория 

**git status** - отобразить статус

**git add "file_name"** добавить fn версионность 

**git reset "file name"** убрать у fn версионность 

**git add .** добавить всем файлам в папке версионность 

**git reset .** убрать у всех файлов в папке версионность 

**git commit -m "commit_name"** зафиксировать файл в дереве с названием CN

**git commit** фиксирует изменения 

**git commit -am** Позволяет пропустит шаг с git add  для файлов с состоянием modified 

**git checkout "hash_number"** Создать перемещение на коммит с hash_number (git checkout main или master- венуться в первичное состояние)

**git diff** Показывает изменения файла на данный момент от последнего коммита 

**git log** Показывает историю коммитов 

**git reflog** Показывает исторю перемещения головы 

**git branch new_branch_name 01234** Создать новую ветку

**git checkout -b branch_name** -Создать ветку с названием branch_name и переместиться в нее.



**git branch branch_name** -Создать ветку с названием branch_name 

**git checkout branch_name** - Переместиться на ветку с названием branch_name 


**cd folder_name** -Погрузиться на 1 уровень вложенности в folder_name 

**cd ..** - Выти из folder_name на 1 уровень вложенности

**git branffffch** -Посмотреть существующие ветки 
