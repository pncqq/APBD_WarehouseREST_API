# 📄 APBD_WarehouseREST_API

Aplikacja **REST API** dla firmy zarządzającej magazynem i produktami. Stworzona z użyciem czystego ADO.NET (SqlConnection) bez ORM (np. EF Core). Projekt zrealizowany w ramach kursu **APBD**.

## 📂 Zawartość repozytorium

- `Controllers/` – logika obsługi endpointów REST
- `Models/` – modele danych
- `Services/` – logika biznesowa
- `Program.cs` – konfiguracja aplikacji
- `appsettings.json` – connection string do bazy danych SQL Server

## ⚙️ Technologie

- ASP.NET Core Web API
- ADO.NET (SqlConnection, SqlCommand)
- SQL Server / LocalDB

## 🚀 Funkcjonalności

- Operacje CRUD na produktach magazynowych
- Obsługa magazynów, zamówień, klientów (w zależności od implementacji)
- Połączenie z relacyjną bazą danych przy użyciu surowych zapytań SQL

## 📅 Kontekst projektu

Projekt skupia się na zrozumieniu podstawowej komunikacji z bazą danych bez użycia ORM. Stanowi fundament do zrozumienia działania Entity Framework poprzez porównanie dwóch podejść.

## 🚀 Jak uruchomić

1. Otwórz projekt w Visual Studio (`WarehouseREST_API.sln`)
2. Skonfiguruj connection string w `appsettings.json`
3. Utwórz bazę danych (ręcznie lub za pomocą skryptów SQL)
4. Uruchom aplikację (`dotnet run` lub F5)

## 👨‍💼 Autor
**Filip Michalski**  
Projekt zrealizowany w ramach zajęć **APBD (Aplikacje Baz Danych)** jako ćwiczenie z czystego ADO.NET i projektowania REST API bez ORM.
