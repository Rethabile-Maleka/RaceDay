# RaceDay System — Part 2: ASP.NET Core REST API


- ASP.NET Core Web API (.NET 8)
- Entity Framework Core Code First + SQL Server
- Password hashing with ASP.NET Core `PasswordHasher<TUser>`
- JWT bearer authentication with role claims
- Swagger/OpenAPI
- xUnit tests
- GitHub Actions build/test workflow

- Organizer: manages only events they created, assigns categories, views enrolments for their events, and records/updates results.
- Participant: views events/categories, enrols in categories, views and cancels their own enrolments, and views their own results.
- Public endpoints: event and category browsing, registration and login.
- Protected endpoints require a bearer token. Use the token returned by login in Swagger's **Authorize** dialog.


Unit tests
Run:
```bash
dotnet test RaceDay.sln
```

