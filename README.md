# GitCheatSheet
Student assignment to learn git commands

### Задание для студентов

Вам нужно пыполнять задяния и вносить изменения в файл README.md, записывая команду, которую вы выполнили.

**Задание 1**. Виберите (локальную) папку для нового проекта и клонируйте в нее данный репозиторий.
```sh
git clone https://github.com/teacher-fiit/GitCheatSheet
```
**Задание 2**. Перейдите в созданную (клон6ированную) папку.

**Задание 3**. Заполните второй столбец таблицы html-файла: после записи каждой ячейки индексируйте измененные файлы и выполняйте коммит.
```sh
git add index.html
git commit -m "git init info"
```
**Задание 4**. Дополните файл style.css. Индексируйте измененные файлы и выполните коммит.
```sh
git add style.css
git commit -m "table header background color"
```
**Задание 5**. Создайте пустой (без файлов) публичный удаленный репозиторий в своем аккаунте на GitHub. 
**Задание 6**. Отправьте изменения на удаленный репозиторий. Если будет необходимость, настройте подключения к удаленному репозиторию.
```sh
git remote set-url https://github.com/ArtMuxomor/zadanie.git
git push https://github.com/ArtMuxomor/zadanie.git main
```
