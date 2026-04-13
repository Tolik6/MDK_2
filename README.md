дравио 
через меню Arrange → Insert → Advanced → Mermaid


1. Переход в папку с кодом
cd /путь/к/вашему/проекту
Замените на реальную папку с вашим кодом.
2. Инициализация репозитория
git init
Создаёт папку .git — Git начинает отслеживать изменения.
3. Добавление файлов в отслеживание
git add .
git status


ЧАСТЬ 2: Связка с GitHub
5. Создать пустой репозиторий на GitHub
GitHub → New repository
Введите имя
НЕ создавайте README, .gitignore, лицензию
6. Добавить удалённый репозиторий
git remote add origin https://github.com/ВАШ_ЛОГИН/ИМЯ_РЕПОЗИТОРИЯ.git
Привязывает локальный Git к GitHub.
7. Отправить код на GitHub
git push -u origin main
Если ошибка, попробуйте git push -u origin master

