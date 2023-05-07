[< на главную](../README.md)

**git push** - отправляет локальные изменения на удаленный репозиторий.

Прежде, чем выполнить данную команду, необходимо сделать предыдущие пункты по содержанию, а именно:
- [git init](/commands/init.md)
- [git add](/commands/add.md)
- [git commit](/commands/commit.md)
- [git branch](/commands/branch.md) (опционально)
- [git remote](/commands/remote.md)

Отправка изменений на удаленный репоиторий:

`git push -u origin main`

, где *origin* - ссылка на удаленный репозиторий куда будет отправлены изменения (см. [git remote](/commands/remote.md)), а *main* - ветка, откуда и куда будут залиты изменения(см. [git branch](/commands/branch.md)).
