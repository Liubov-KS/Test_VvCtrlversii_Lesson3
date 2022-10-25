## Привет!

Тефтелька - замечательный котик )))

Однозначно!)

1. Создали аккаунт на Github.com
2. Создать локальный репозиторий
3. "Подружить" ваш локальный и удаленный репозитории (Github подскажет как:)
4. Отправить (push) ваш локальный репозиторий на удаленный (на Github). При этом,вам, возможно нужно будет авторизоваться на удаленном репозитории
5. Провести изменения с "другого компьютера"
6. Выкачать (pull) актуальное состояние из удаленного репозитория


Регистрируемся на гитхаб и создаем свой репозиторий:

…or create a new repository on the command line (в терминале задать команды:)
echo "# Test_VvCtrlversii_Lesson3" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/Liubov-KS/Test_VvCtrlversii_Lesson3.git

git push -u origin main

…or push an existing repository from the command line

__git remote add origin__ https://github.com/Liubov-KS/Test_VvCtrlversii_Lesson3.git

__git branch -M main__    /основная ветка будет ветка "main"

__git push -u origin main__ /направить инфо отсюда в оригинальную (удаленную ветку на Github) - ветку "main"
