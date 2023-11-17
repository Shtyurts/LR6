# LR6
Лабораторная работа №6
## Копия репозитория лабораторной работы в личное хранилище
![Копия репозитория лабораторной работы в личное хранилище](screenshots/Снимок экрана 2023-11-17 004017.jpg)
## Клонирование личного удалённого репозитория на компьютер
![Клонирование личного удалённого репозитория на компьютер](screenshots/Снимок экрана 2023-11-17 004127.jpg)
## Добавление файла через интерфейс GitHub
![Содержимое файла](screenshots/Снимок экрана 2023-11-17 004307.jpg)
## Получение истории операций ветки master
![История операций master](screenshots/Снимок экрана 2023-11-17 004426.jpg)
## Получение истории операций ветки branch1
![История операций branch1](screenshots/Снимок экрана 2023-11-17 004611.jpg)
## Последние изменения
![Последние изменения](screenshots/Снимок экрана 2023-11-17 005101.jpg)
## Конфликт при попытке слияния
![Конфликт](screenshots/Снимок экрана 2023-11-17 005817.jpg)
## Разрешение конфликта
![Разрешение конфликта](screenshots/Снимок экрана 2023-11-17 005759.jpg)
## Удаление побочной ветки
![Удаление ветки](screenshots/Снимок экрана 2023-11-17 011107.jpg)
## Создание коммитов для отката
![Создание коммитов для отката](screenshots/Снимок_экрана_2023-11-17_012214.jpg)
![Создание коммитов для отката](screenshots/Снимок экрана 2023-11-17 012930.jpg)
## Откат коммита
![Откат коммита](screenshots/Снимок экрана 2023-11-17 013203.jpg)
## Лог команд
```
git clone https://github.com/Shtyurts/LR6
cd LR6/
git pull
git log
git checkout branch1
git log
git status
git show
git checkout master
git show
git merge branch1
git merge branch1
git add .
git status
git merge branch1
git commit -m "Merge branch1->master"
git branch -d branch1
git push origin -d branch1
git add .
git status
git commit -m "Добавлен файл added_file в качестве изменения"
git add .
git status
git commit -m "В качестве изменения изменено наполнение файла added_file"
git status
git reset --hard HEAD~
git status
git branch protocol
git push origin protocol
git checkout protocol
git add .
git status
git commit -m "Добавлены скриншоты хода выполнения работы"
git push origin
git push origin protocol
```

## История операций в форматированном виде
```
368f989, Fri Nov 17 01:58:11 2023 +0300, Shtyurts, Добавлены скриншоты хода выполнения работы
5961ae2, Fri Nov 17 01:20:53 2023 +0300, Shtyurts, Добавлен файл added_file в качестве изменения
4e90c96, Fri Nov 17 01:00:15 2023 +0300, Shtyurts, Merge branch1->master
ffab79a, Fri Nov 17 00:42:05 2023 +0300, Shtyurts, Create file_interface
921f53b, Sat Nov 21 20:09:49 2020 +0300, Kurtyanik, Обновление информации
0f9f50d, Sat Nov 21 20:08:33 2020 +0300, Kurtyanik, Заполнил файл
c08a654, Sat Nov 21 20:02:16 2020 +0300, Kurtyanik, Файл создан пустым
3c6e913, Sat Nov 21 19:58:20 2020 +0300, Kurtyanik, Initial commit
```

# Вывод
Были изучены базовые возможности системы управления версиями, получен опыт работы с Git Api, опыт работы с локальным и
удаленным репозиторием.
