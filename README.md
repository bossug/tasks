# tasks
#создание файла с комментом
echo "# tasks" >> README.md

#Создание списка
git init

#Добавить в индекс
git add README.md

#Добавить коммит
git commit -m "Справка"

#Подключиться к репозиту
git remote add origin git@github.com:bossug/tasks.git

#Записать
git push -u origin master
