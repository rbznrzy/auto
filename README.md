﻿# QA-AUTO-7  

## Description
**QA-AUTO-7** is repository which created for studying autotamatisation testing.

During a work in my current workplace i tried to make a e2e aouto-test on my project. And i had kinda a success, but I realize that I only reproduce the specs, which was created by my co-workers and I have no idea how to make it from scratch.  
So I made a decision that I need to get this course, because I am interesting in automatisation testing from the start of my trying to create the first one.  
And I have a huge loyalty after passing Manual Testing course, so i don't have another options except IT-Switcher School.

And now I'm here.

I suppose that README.md will be filled after completing tasks.  
So that I really don't know why I type it in English, but I will be completing tasks on russian language.  

Practice makes perfect

## Home works
### hw 1.1.3
`git fetch` - данная команда позволяет получить изменения с удаленного репозитория, которых нет в локальном репозитории. При этом данные с удаленного репозитория не сливаются с данными в текущей ветке локального репозитория. Для того, чтобы слить данные с удаленного и локальных репозиториев, необходимо  выполнить команду `git merge`

`git pull` - при выполнении данной команды данные с удаленного репозитория сразу сливаются с данными из локального репозитория. 

**Вывод:** выполнение команды `git pull` последовательно выполняет сценариии `git fecth` и `git merge`.  С одной стороны это может показаться удобным, с другой это может привести к появлению конфликтов, если данные на удаленном и локальных оепрозиториях отличаются.

### hw 1.1.4
`git commit --amend` - команда, позволяющая присоединить новые изменения в предыдущий коммит. 
В данном случае последовательность действий выглядит следующим образом:
1. Внести изменения в файлы
2. Выполнить команлу `git add --all`, чтобы индексировать внесенные изменения
3. Выполнить команду `git commit --amend`

Так же можно изменить комментарий последнего коммита выполнив команду `git commit --amend -m "new message"`

