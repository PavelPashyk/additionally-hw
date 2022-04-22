git init Инициализация репозитория
git status Проверка статуса репозитория
git branch Просмотр списка веток
git branch ivan-ivanov Создать новую ветку из ветки 
git checkout ivan-ivanov Переход в нужную ветку 
git add "имя" или просто git add . Внесение изменения только выбранного файла или всего
git commit -m "init(hw-1)" Комментарий к сохранению 
git push origin имя  ветки отправим изменения на **github** 

создание с нуля + инициализация
echo "# additionally-hw" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin путь с github
git push -u origin main