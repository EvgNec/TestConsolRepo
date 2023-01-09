# TestConsolRepo

1. git clone клонування репозіторія на PC
2. git branch header свторюємо нову гілку для роботи
3. git branch список доступних гілок
4. git checkout header перейти до гілки
   2+4. git checkout -b header
5. git status наступна дія
6. git add . добавити відстеження
7. git commit -m "first commit" комміт
8. git push --set-upstream origin header добавити гілку у репозіторій
   gip push -u origin header
9. git pull получити зміни
10. 6+7 git commit -am "add"
11. git merge header
12. git branch -d header видалити гілку з проєкту локально
13. git branch origin --delete header видалення на гіті
    git push origin --delete header

Користні команди
git clone - Клонує репозиторій
git pull - Стягує оновлення з репозиторію
git push - Записує оновлення коду на віддалений репозиторій
git status - показує статус в локальному репозитрії
git add . - гіт починає відслідковувати зміни що внесені в файл
git commit -m “commit text” - зберігає поточний стан файла
git commit -am “text commit ” - короткий запис команда git add . та git commit -m “” (Працює лише для вже відстежуваних файлів)
git log - показує історію комітів
git branch - показує список локальних гілок
git branch name - створює гілку з ім’ям name
git branch -a - показує список віддалених гілок
git checkout -b name - створює нову гілку з ім’ям “name” і переходить в неї
git checkout name - перехід до потрібної гілки
git merge name - злятя гілки “name” в поточну
git merge --abort - відміна злиття гілок
git push -u origin name - перший пуш нової локальної гілки на гітхаб
git branch -d name - видалення локальної гілки (потрібно з неї вийти)
git push origin --delete name - видалення віддаленої гілки на гітхабі
git stash - ховає внесені зміни в “карман”. (Використовується тоді коли потрібно перейти в іншу гілку але не хочеться робити коміт)
git stash apply - відновлює код з “кармана” (Повертає схований код)
Для першого запуску gulp збірки
$ npm install
$ gulp
Для наступних запусків збірки
$ gulp
Щоб закінчити роботу gulp
Ctrl + C
