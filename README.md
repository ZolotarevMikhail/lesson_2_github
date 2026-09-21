Что это: учебный проект урока: создание первого репозитория Git, работа с папкой проекта и коммитами, публикация на GitHub.
Как запустить:
- в VSCode создать файл Main.py с кодом: print("Hello, World!"), сохранить;
- установить Git, проверить: git --version;
- Настроить подпись и почту: git config --global user.name и git config --global user.email, проверить: git config --global --list;
- создать репозиторий в папке проекта: git init;
- добавить файл Main.py: git add main.py;
- создать commit: git commit -m "First commit", проверить: git status;
- создать файл README.md, добавить: git add .;
- создать commit: git commit -m "Add README.md", проверить: git log;
- установить Github и создать репозиторий lesson_2_github;
- связать Git и Github: git remote add origin https://github.com/ZolotarevMikhail/lesson_2_github.git и git push -u origin main;
- репозиторий создан.
Что я сделал в этом уроке:
- установил Git и Github на комп, настроил подпись и почту, сделал два коммита и зафиксировал в локальном репозитории;
- создал публичный репозиторий, связал Git и Github и перенес данные в публичный репозиторий.
Что было сложным: в целом весь процесс непростой для понимания и лучше всего этому процессу помогло выполнение ДЗ.
История коммитов: было два коммита, первый - создание и фиксация файла с кодом Main.py, второй - файл с описанием процесса README.md.
