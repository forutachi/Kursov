# ASP.NET Core Fines Management System

Это веб-приложение на ASP.NET Core для управления штрафами, пользователями и ролями.

## 🚀 Быстрый старт

### 1. Клонировать проект
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

Проверь подключение к базе данных в appsettings.json:

json
Копировать
Редактировать
"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=MyFineDb;Trusted_Connection=True;"
}

Выполни миграции:

bash
Копировать
Редактировать
dotnet ef database update
3. Запустить приложение
bash
Копировать
Редактировать
dotnet run
Приложение будет доступно по адресу: https://localhost:5001 или http://localhost:5000

Структура проекта
Models/ — модели данных (Users, Fines и т.д.)

Data/ — контекст базы данных и миграции

Controllers/ — контроллеры MVC

Views/ — Razor-шаблоны

wwwroot/ — статические файлы

appsettings.json — конфигурация
