## Проект по django "Запись на тестдрайв"
### Руководство пользователя.
Проект представляет собой сайт из 3-х страниц с функцией записи на тестдрайв
На главной странице отображаются активные записи и данные клиентов
<img width="725" height="402" alt="image" src="https://github.com/user-attachments/assets/e32ed46b-764b-4e38-bb84-cdfa0eba49c9" />
На странице О компании отображается история нашей компании
<img width="954" height="526" alt="image" src="https://github.com/user-attachments/assets/1fcb705c-2543-4ccd-9dba-8d64d80a3069" />
На странице тест драйв у нас форма заполнения
<img width="847" height="654" alt="image" src="https://github.com/user-attachments/assets/d88c9d62-5468-4824-a44f-d20032eb43c4" />

### Руководство программиста
> Django - это высокоуровневый Python веб-фреймворк, который позволяет быстро создавать безопасный  и поддерживаемый веб-сайты.
Начало работы со средой:
```
# Создаю вирт. среду
python -m venv .venv
# Активирую вирт. среду
.venv\Script\activate
# Устанавливаю библиотеку
pip install django==5
# Создаю проект
django-admin startproject testdrive
# Перехожу к папке проекта
cd testdrive
# Создаю приложение
python manage.py startapp myapp
# Перейдите в файл settings.py и в разделе INSTALLED_APPS впишите
# Запускаю проект
python manage.py runserver
```
