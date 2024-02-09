# YaTube API - социальная сеть  

## Описание 
Yatube - проект который является реализацией REST API для блога 
Реализованы следующие возможности:
* Публикация записей 
* Комментарий записей 
* Подписка на автора
* Фильтровация по полям 

### Технология 
![python](https://img.shields.io/badge/Python-100000?style=for-the-badge&logo=python&logoColor=white) ![django](https://img.shields.io/badge/django-100000?style=for-the-badge&logo=django&logoColor=white) ![django rest](https://img.shields.io/badge/django%20rest-100000?style=for-the-badge&logo=django&logoColor=white) ![sqlite](https://img.shields.io/badge/SQLite-100000?style=for-the-badge&logo=sqlite&logoColor=white) ![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) ![vscode](https://img.shields.io/badge/VSCode-100000?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

## Запуск проекта 
Клонировать репозиторий:

```
git clone git@github.com:Ilnurr/api_final_yatube.git 
```

Перейти в репозиторий:

```
 cd api_final_yatube
```

Создать виртуальное окружение:

```
python3 -m venv env
```

Активировать виртуальное окружение:

```
source env/bin/activate 
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt 
```
 
Выполнить миграции:

```
python3 manage.py migrate 
```

Запустить проект:

```
python3 manage.py runserver
```
