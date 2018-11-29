"# todoapp" 

dotnet restore
dotnet run
dotnet add package Microsoft.EntityFrameworkCore

dotnet restore
dotnet ef migrations add InitialCreate
dotnet ef database update



#http://sqlitebrowser.org/