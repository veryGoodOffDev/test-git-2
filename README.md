1.git status
2.git add [files] добавляет фалы в stage (через . все файлы)
3.git commit -m "комментарий о проделанной работе в файлах"
4.git log / git log --oneline
5.git push [rep_link] [branch_name]

git push origin master


можно создать несколько веток
master
develop
feature/main-page 1 разработчик тут работает, другой в другой ветке и так они не мешают друг другу
feature/about-company

команада git branch показывает ветки, ветка выделенная зеленым, это та ветка в которой мы находимся
переключение ветки происходит с помощью git checkout (название ветки)
например git checkout develop

перенести из ветки в develop в ветку master есть 2 способа, 1й на гитхаб вкладка pull requests
git pull origin подгружает из облака слитую ветку, которую мы слили с мастером