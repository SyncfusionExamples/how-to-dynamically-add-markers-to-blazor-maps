# Dynamic Marker Addition in Syncfusion Blazor Maps (Blazor MAUI)

## Overview
This project demonstrates how to dynamically add markers to the **Syncfusion Blazor Maps** component within a **Blazor MAUI** application. It focuses on showing how map markers can be updated at runtime using a data-bound approach, allowing the UI to refresh automatically when the underlying data changes. The example uses OpenStreetMap as the base map and highlights interactive behavior through user actions.

## Project Purpose
The primary purpose of this project is to illustrate a clean and practical pattern for managing map markers dynamically in a Blazor environment. By leveraging data binding and observable collections, the Maps component reacts instantly to updates without requiring manual refresh logic.

## Key Features
- Integration of Syncfusion Blazor Maps in a Blazor MAUI application  
- Display of markers on top of OpenStreetMap  
- Dynamic marker updates using an `ObservableCollection` data source  
- Button-driven interaction to add multiple markers at runtime  
- Automatic UI refresh when the marker data source changes  

## Technologies Used
- Blazor MAUI  
- Syncfusion Blazor Maps  
- OpenStreetMap  
- .NET ObservableCollection  

## How It Works
The application maintains a marker data source defined as an `ObservableCollection` containing marker objects. Initially, the map is rendered without additional markers. When the **Add Marker** button is clicked, three new marker objects are added to the collection. Because the Maps component is data-bound to this collection, the newly added markers are immediately rendered on the map.

## Usage
1. Run the Blazor MAUI application.
2. View the map rendered with OpenStreetMap tiles.
3. Click the **Add Marker** button.
4. Observe three new markers appear instantly on the map.

## Use Cases
This approach is useful for scenarios such as:
- Tracking locations dynamically
- Visualizing real-time data points
- Building interactive map-based user interfaces

## Notes
The example is intentionally minimal and focused on marker updates. It can be extended further to include marker customization, event handling, or integration with live data sources.