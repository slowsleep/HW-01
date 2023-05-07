[< на главную](../README.md)

**git config** - выводит информацию по проекту git

Вывести все переменные конфига:
`git config --list`

Изменить глобально имя и почту пользователя, что будет пушить в удаленный репозиторий:

`git config --global user.name "Name"`

`git config --global user.email mail@mail.ru`

Чтобы применить изменения переменных локально (только в текущей директории), то надо поменять ключ `--global` на `--local`.