## git push
```bash
git push [--all | --branches | --mirror | --tags] [--follow-tags] [--atomic] [-n | --dry-run] [--receive-pack=<git-receive-pack>]
	   [--repo=<repository>] [-f | --force] [-d | --delete] [--prune] [-q | --quiet] [-v | --verbose]
	   [-u | --set-upstream] [-o <string> | --push-option=<string>]
	   [--[no-]signed|--signed=(true|false|if-asked)]
	   [--force-with-lease[=<refname>[:<expect>]] [--force-if-includes]]
	   [--no-verify] [<repository> [<refspec>…​]]
```
***git push*** производит отправку ваших изменений в репозиторий. Если вы и другой разработчик одновременно клонируете, затем он выполняет команду *push*, то, если после него вы попытаетесь выполнить команду *push*, ваш *push* точно будет отклонён. Для внесения ваших изменений вам требуется получить изменения с удалённого репозитория и слить их с вашим программным кодом.

[Главная страница](./readme.md)