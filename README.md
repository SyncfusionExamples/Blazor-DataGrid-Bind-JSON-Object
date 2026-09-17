# Blazor DataGrid - Bind JSON Object to Grid

## Overview

This sample demonstrates how to bind JSON data to the Syncfusion Blazor DataGrid and display the records in a tabular format. The application loads data from a JSON source, maps it to a C# model, and uses that collection as the grid data source. This approach is useful when application data originates from JSON files, APIs, configuration sources, or external services that return JSON payloads.

## Key Features

- Uses the Syncfusion Blazor DataGrid (`SfGrid`) to display JSON-backed records.
- Binds a strongly typed collection generated from JSON data to the grid data source.
- Demonstrates mapping JSON properties to a C# model defined in `GridData.cs`.
- Renders model fields through grid column definitions in the page hosting the DataGrid.
- Loads and processes data stored in `bind-data.json` before assigning it to the grid.

## Prerequisites

* Visual Studio 2022  or Visual Studio Code

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `BindJsonObject.sln` in Visual Studio 2022.
3. Restore the NuGet packages for the solution.
4. Build the project to ensure all dependencies are available.
5. Run the application using Visual Studio.
6. Navigate to the page that hosts the Syncfusion DataGrid to view records loaded from the JSON source.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

## Project Structure

- `Pages/` — contains the Razor page that renders the Syncfusion Blazor DataGrid and performs JSON data binding.
- `GridData.cs` — defines the model used to deserialize and represent the JSON records displayed in the grid.
- `bind-data.json` — JSON data source consumed by the sample.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Refer to the Syncfusion Blazor DataGrid documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/data-binding/data-binding

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
