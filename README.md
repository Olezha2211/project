# Выполнение 11-го домашнего задания к модулю:  

1. Создаю новый проект Visual Studio Code под названием "MyProject".
2. Делаю инициализацию GIT с помощью команды:  
`git init`
3. Регистрирую имя и емейл если ранее этого не делал:  
`git config --global user.name "Name"`
`git config --global user.email "Name@ukr.net"`
4. Создаем файл .gitignore в корневой папке проекта. Дальше в файле прописываю следующее:      
```
*.sass
bin/
admin/
config/
.getignore
``` 
5. Добавляем все файлы в локальное хранилище с помощью команды:  
`git add .` - Добавляем все файлы в статус ожидания,
`git commit -m "Add all files"` - Добавляем все файлы в локальный репозирторий.
6. Создаю новую ветку и перехожу в неё:  
`git branch authorisation` - создание ветки
`git checkout authorisation` - переход на созданную ветку.
7. В новой ветке создаю папку **blog** с файлами: **index.js, index.html**.
8. Добавляю папку blog в ожидание и выгружаю в локальный репозиторий:  
`git add blog/`
`git commit -m "add new branch authorisation`
9. Перехожу на основную ветку master:  
`git checkout master`
10. Регистрируюсь на GitHub так же проделовую все для того чтобы можно было выгружать на отдаленный репозиторий. Делаю подключения к отдаленному репозиторию:  
`git remote add origin https://github.com/Olezha2211/project.git`
11. Выгружаю основную ветку проекта на отдаленный репозиторий.  
`git push -u origin master`

## Спасибо за внимание!