# CmsShoppingCart

This is a minimal ASP.NET Core Razor Pages application. The project can serve as a foundation for a shopping cart or lightweight CMS.

## Requirements

- .NET 8 SDK (see `global.json`)

## Running locally

```bash
# restore dependencies and run the site
cd CmsShoppingCart
 dotnet run
```

The app listens on `https://localhost:5001` by default.

### Using Docker

You can also run the application in a container:

```bash
docker compose up --build
```

Then browse to `http://localhost:8080`.

## Tests

A small xUnit test project is provided. Run tests with:

```bash
dotnet test
```

## Project structure

- `CmsShoppingCart/` - main web application
- `tests/` - xUnit test project
- `wwwroot/` - static assets
- `Pages/` - Razor Pages

## Continuous Integration

GitHub Actions restore, build and test the app on every push.
