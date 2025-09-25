# Лабораторная работа №1: Nginx + Docker

## 👩‍💻 Автор
ФИО:Быкова Анастасия Игоревна  
Группа: 3МО-1

---

## 📌 Описание задания
Создать веб-сервер в Docker с использованием Nginx и подключить HTML-страницу.  
Результат доступен по адресу [http://localhost:8080](http://localhost:8080).

---

## ⚙️ Как запустить проект

1. Клонировать репозиторий:
   ```bash
   git clone <https://github.com/anaaastuas/1lab_webdevel>
   cd nginx-lab
Запустить контейнеры:
```bash
docker-compose up -d --build
```
Открыть в браузере:
```http://localhost:8080```
📂 Содержимое проекта

```docker-compose.yml``` — описание сервиса Nginx

```code/index.html``` — главная HTML-страница

```screenshots/``` — все скриншоты

📸 Скриншоты работы

✅ Результат
Сервер в Docker успешно запущен, Nginx отдаёт мою HTML-страницу.
