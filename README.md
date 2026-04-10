# dotnet-aspnet

A minimal ASP.NET Core web application built with .NET 9.

## Overview

This project demonstrates a basic ASP.NET Core web server with OpenAPI/Swagger support. It serves a simple "Hello World" response at the root endpoint.

## Requirements

- [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)

## Getting Started

```bash
dotnet run
```

The server will start and listen on the default port. Visit `http://localhost:8080` to see the response.

## Endpoints

| Method | Path | Description       |
|--------|------|-------------------|
| GET    | `/`  | Returns "Hello World" |

## Dependencies

- `Microsoft.AspNetCore.OpenApi` 9.0.0
- `Swashbuckle.AspNetCore` 6.5.0
