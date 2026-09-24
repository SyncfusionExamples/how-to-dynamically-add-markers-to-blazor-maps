# Dynamically Add Markers in Syncfusion Blazor Maps

## Overview

This sample demonstrates how to dynamically add markers to the Syncfusion [Blazor Maps](https://www.syncfusion.com/blazor-components/blazor-map) component at runtime. The implementation uses an `ObservableCollection` as the marker data source and updates the collection through a user action. When new marker objects are added, the map automatically reflects the changes without requiring a manual refresh. The sample renders the markers on top of OpenStreetMap tiles, making it useful for applications that need to display live or user-generated location data.

## Key Features

- Uses the Syncfusion Maps component to render an interactive map with OpenStreetMap tiles.
- Stores marker information in an `ObservableCollection`, enabling automatic UI updates when data changes.
- Provides an **Add Marker** action that appends additional marker records at runtime.
- Demonstrates dynamic marker rendering based on changes in the bound marker data source.
- Shows how multiple location entries can be inserted into the collection and immediately displayed as markers on the map.
- Uses data-bound marker rendering rather than static marker definitions.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `MauiAppMapsVersion7.csproj` project or the solution file if available.
3. Restore all NuGet packages.
4. Ensure the MAUI Blazor application is configured as the startup project when required.
5. Build the project.
6. Run the application using `Ctrl+F5`.
7. The application launches as a .NET MAUI Blazor app and displays the sample page containing the Maps component.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory containing `MauiAppMapsVersion7.csproj`.

```bash
dotnet restore
dotnet run
```

5. Launch the application using a supported .NET MAUI environment and view the page that hosts the Maps sample.

## Project Structure

`Pages/Index.razor` — contains the Syncfusion Maps implementation, marker data binding logic, and runtime marker addition workflow.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor Maps marker documentation: https://help.syncfusion.com/chart-sdk/blazor/maps/markers

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.