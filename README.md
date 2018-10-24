# tasks
#создание файла с комментом\n
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


#Изменение
git commit -m "text"
git push origin master
