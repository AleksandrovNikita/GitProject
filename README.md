# GitProject
Данный проект поможет отработать команды Git на примере командного проекта

✅ Что нужно сделать
1. Настроить Git (если не сделали этого раньше)
bash
git config --global user.name "Имя Фамилия"
git config --global user.email "email@example.com"

2. Склонировать текущий репозиторий
bash
git clone <ссылка-от-преподавателя>
cd recipe-book
git status

3. Создать свою ветку
bash
git checkout -b feature/recipe-<название>

4. Добавить свой рецепт в Книгу рецептов

5. Закоммитить и отправить
bash
git add recipes/<название>.md
git commit -m "feat: добавлен рецепт <название>"
git push origin feature/recipe-<название>

6. Запустить Pull Request вашей ветки на main

7. Обновить локальный main (убедиться, что изменения применились)
bash
git checkout main
git pull origin main
ls recipes/
