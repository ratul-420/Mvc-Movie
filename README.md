# Mvc-Movie

ASP.NET Core MVC tutorial project (MvcMovie), built step by step following the
Microsoft Learn documentation. Each commit corresponds to one chapter.

- **Author:** Ratul Fahim Muntashir
- **Neptun code:** H1566N
- **Database:** PostgreSQL (instead of SQL Server)

## Run it
1. Install the .NET 10 SDK and PostgreSQL, and start PostgreSQL.
2. Set the connection string `MvcMovieContext` in `MvcMovie/appsettings.json`
   (host, port, database `MvcMovie`, your PostgreSQL username).
3. Apply the migrations and start the app:
```bash
   cd MvcMovie
   dotnet ef database update
   dotnet run
```
4. Open `http://localhost:5197/Movies`.

## Chapters
1. Get started
2. Add a controller
3. Add a view
4. Add a model
5. Work with a database
6. Controller methods and views
7. Add search
8. Add a new field
9. Add validation
10. Examine the Details and Delete methods