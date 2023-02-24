## Instruction for GIT

# Instalation

*download GIT from this site*:
<code>[site of GIT](https://git-scm.com/downloads)</code>

![image of site](instalation.jpg)

__*Choose all necessary settings*__

# Basic commands of GIT

* __git config --global user.name "Tara Routray"__ — *add name of user*
* __git config --global user.email "dev@anemail.com"__ — *add email of user*
* __git init__ — *it will create a hidden folder. It contains all the objects and references that Git uses and creates in the project history*
* __git commit -m__ — *commentary for changes of file*
* __git add ...__ — *Add a separate file to the Prepared Files area*
* __git add .__ — *add all files to the Prepared Files area*
* __git status__ — *View the status of the desired repository*
* __git log__ — *View changes made to the repository*

# Commands for interaction with branches

* __git branch new_branch_name__ — *Создать новую ветку с именем new_branch_name*
* __git checkout -b new_branch_name__ — *Создать ветку с именем new_branch_name и перейти на неё*
* __git branch__ — *просмотреть список веток*
* __git branch -a__ — *Просмотреть список удалённых веток*
* __git branch -d existing_branch_name__ —*Удалить ветку с именем existing_branch_name*
* __git branch -D existing_branch_name__ — *Принудительно удалить ветку независимо от текущего статуса и без предупреждений*
* __git push origin --delete existing_branch_name__ — *Удалить ветку в удалённом репозитории*
* __git merge existing_branch_name__ — *Выполнить слияние двух веток*
* __git merge --no-ff existing_branch_name__ — *Выполнить коммит слияния*
* __git log --graph --oneline --decorate__ — *Посмотреть историю коммитов в виде графика для текущей ветви*
* __git log --all --graph --oneline --decorate__ — *Просмотреть историю коммитов в виде графика для всех веток*
* __git merge --abort__ — *Прекратить слияние*
* __git reset__ — *Восстановить конфликтующие файлы до стабильного состояния.*

# Commands for interacting with remote repository

* __git remote add awesomeapp https://github.com/someurl..__ — *Добавить удалённый репозиторий*
* __git clone__ — *Склонировать внешний репозиторий на ПК*
* __git push__ — *Отправить версию репозитория на внешний репозиторий*
* __git remote -v__ — *Просмотреть удалённые URL-адреса*
* __git remote show origin__ — *Получить подробные сведения об удалённом репозитории*
* __git push origin main__ — *Отправить изменения в удалённый репозиторий с указанием имени репозитория и ветки*
* __git pull__ — *Получить изменения из удалённого репозитория*
* __git pull --verbose__ — *просмотреть подробные сведения о загруженных файлах*
* __git merge origin__ — *Слияние удалённого репозитория с локальным с указанием имени удалённого репозитория*
* __git push -u origin new_branch__ — *Передать новую ветку в удалённый репозиторий*
* __git rebase branch_name__ — *Использование перебазирования*