# Blazor with LibMan

This sample demonstrates how to effectively use the [Library Manager (LibMan)](https://learn.microsoft.com/aspnet/core/client-side/libman) to manage client-side dependencies in a modern Blazor application. LibMan provides a lightweight alternative to npm for managing libraries like Bootstrap, Syncfusion themes, and other client-side assets directly within Visual Studio.

Whether you're new to Blazor or looking to simplify your library management workflow, this project shows best practices for integrating LibMan with Blazor's component-based architecture.

## Features

- **LibMan Integration** - Efficient client-side library management without node_modules
- **Theme Support** - Pre-configured Bootstrap 5 themes for UI components
- **Razor Components** - Modern interactive server-side rendering with Blazor
- **Responsive Layout** - Built-in navigation and layout components
- **Development-Optimized** - Hot reload and debugging support

## Prerequisites

- [.NET SDK 9.0](https://dotnet.microsoft.com/download/dotnet/9.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-libman.git
cd blazor-libman
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

- [Library Manager (LibMan) Guide](https://learn.microsoft.com/aspnet/core/client-side/libman)
