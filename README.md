### Git

1. [Создание и клонирование](./create&clone.md)
2. [Добавление изменений, коммит и отправка изменений](./add&commit&push.md)




// ls : файлы и папки
// clear :
 revert xxxxx - удаление изменений комита ххххх

// git log - показывает комментарии
// git show xxxxx - раскрывает комит или тэг
// git log --oneline --graph - графическая схема коммитов и веток (если добавить после "граф" "имя" ветки
// то отобразится ее коммиты)
// git log -- 'file' - показывает коммиты связанные с файлом
// git log -p -- 'file' - показывает коммиты, связанные с файлом, и изменения внесенные в коммитах


// git - краткая справка
// git help 'command' - справка по команде

// git branch 'name' - создание новой ветки
// git branch - отображение всех веток
// git checkout 'name' - переход на ветку

// git merge --no--ff 'name' - слияние ветки с мэйн (после коммит и пуш)

// git tag -a v1.0 - "Version 1.0" - создание тэга (отметка на определенном коммите)
// git push --tags - отправка тэга при пуше