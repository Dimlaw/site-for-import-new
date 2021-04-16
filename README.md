# site-for-import-new. Описание порядка действий
1. создать локальный репозиторий
2. cоздать файл .gitignore
3. Внести изменения в .gitignore
4. сделать git add файла .gitignore
5. проверить git status
6. Если все в порядке, сделать commit изменений
7. Проверить связь локального репозитория git remote -v
8. Меняем origin на github (в задании target)
9. $ git remote -v
github  https://github.com/Dimlaw/site-for-import-new.git (fetch)
github  https://github.com/Dimlaw/site-for-import-new.git (push)
origin  git@github.com:Dimlaw/site-for-import-new.git (fetch)
origin  git@github.com:Dimlaw/site-for-import-new.git (push)
10. $ git remote rm origin
11. $ git push -u github main


