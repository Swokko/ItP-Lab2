# GitCheatSheet
Student assignment to learn git commands

### Задание для студентов

Вам нужно пыполнять задяния и вносить изменения в файл README.md, записывая команду, которую вы выполнили. Нужно заменить текст в треугольных скобках командой.

**Задание 1**. Виберите (локальную) папку для нового проекта и клонируйте в нее данный репозиторий.
```sh
git clone https://github.com/teacher-fiit/GitCheatSheet.git
```
**Задание 2**. Перейдите в созданную (клонированную) папку.
```sh
~/Projects/University/Introduction To Profession/Lab2 master*
❯ cd GitCheatSheet/
```

**Задание 3**. Заполните второй столбец таблицы html-файла. После заполнения каждой ячейки индексируйте измененные файлы и выполняйте коммит.
```sh
git add .
git commit -m "Добавлено описание команды git init"
git add .
git commit -m "Добавлено описание команды git clone url"
git add .
git commit -m "Добавлено описание команды git add file"
git add .
git commit -m "Добавлено описание команды git add ."
git add .
git commit -m 'Добавлено описание команды git commit -m "comment"'
git add .
git commit -m 'Добавлено описание команды git commit -a -m "comment"'
git add .
git commit -m 'Добавлено описание команды git push url'
git add .
git commit -m 'Добавлено описание команды git status'
git add .
git commit -m 'Добавлено описание команды git log'
git add .
git commit -m 'Добавлено описание команды git branch branch_name'
git add . 
git commit -m 'Добавлено описание команды git checkout branch_name'
git add . 
git commit -m 'Добавлено описание команды git checkout -b branch_name'
git add .
git commit -m 'Добавлено описание команды git remote'
```
**Задание 4**. Дополните файл style.css. Создайте и примените на странице не менее 5-ти стилей. Индексируйте измененные файлы и выполните коммит.
```sh
git add .
git commit -m 'Обновлена таблица стилей style.css'
```
**Задание 5**. Создайте пустой (без файлов) публичный удаленный репозиторий в своем аккаунте на GitHub. 

**Задание 6**. Отправьте изменения на удаленный репозиторий. Если будет необходимость, настройте подключения к удаленному репозиторию.
```sh
git remote remove origin
git remote add origin git@github.com:Swokko/ItP-Lab2.git
git push -u origin --all
```
