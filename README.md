### Getting Started

Demo pulled from: https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio-code

1. Make sure to have installed .NET SDK
2. Create project (if not already done) by `dotnet new webapi -o TodoApi`, where webapi is the type of project and TodoApi is the name of the project
3. cd into TodoApi/
4. Run `dotnet add package Microsoft.EntityFrameworkCore.SqlServer`
5. Run `dotnet add package Microsoft.EntityFrameworkCore.InMemory`
6. In folder, run `dotnet dev-certs https --trust`
7. In VS Code, press `Ctrl + F5` to start the server
8. Go to `localhost:5001/weatherforecast` to see a JSON response