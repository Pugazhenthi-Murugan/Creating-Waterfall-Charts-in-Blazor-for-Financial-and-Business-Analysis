# Creating Waterfall Charts in Blazor for Financial and Business Analysis

Build interactive waterfall charts in Blazor to visualize financial data flows, revenue breakdowns, and business metrics using Blazor Charts.

## Overview

This sample demonstrates how to create professional waterfall charts in Blazor applications using Blazor Charts component. Waterfall charts are ideal for visualizing cumulative effects of sequential financial data, showing how an initial value is affected by a series of positive or negative values.

### What You'll Learn

- Building interactive waterfall charts with Blazor
- Configuring chart series, axes, and formatting
- Working with Syncfusion Blazor Charts component
- Displaying financial data with intermediate and final sum points
- Implementing tooltips and data labels for better visualization

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/Creating-Waterfall-Charts-in-Blazor-for-Financial-and-Business-Analysis.git
cd Creating-Waterfall-Charts-in-Blazor-for-Financial-and-Business-Analysis
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

## Features

- **Waterfall Chart Visualization** - Display financial flows with positive and negative values
- **Interactive Elements** - Hover tooltips showing detailed value information
- **Intermediate Sums** - Mark cumulative points within the chart (e.g., Gross Profit)
- **Final Sums** - Highlight total calculations (e.g., Net Profit)
- **Responsive Design** - Charts adapt to different screen sizes
- **Bootstrap Theming** - Built-in Bootstrap 5 styling for professional appearance
- **Data Labels** - Display values directly on chart bars

## Key Components

### Home.razor
The main page containing the waterfall chart implementation. It demonstrates:
- Creating a waterfall chart with Syncfusion's `SfChart` component
- Configuring chart series with `ChartSeries` of type `Waterfall`
- Setting up primary X and Y axes
- Adding tooltips and data labels
- Defining intermediate and final sum points

## Technology Stack

- **.NET 9** - Modern .NET runtime
- **Blazor Server** - Interactive server-side Blazor components
- **Syncfusion Blazor Charts (v29.1.38)** - Professional charting component
- **Bootstrap 5** - Responsive UI framework
- **C#** - Primary programming language

## Resources

- [Waterfall Chart Guide](https://www.domo.com/learn/charts/waterfall-charts)
- [Waterfall Chart Definition, Use Cases, and Anatomy](https://www.visualizing.org/waterfall-chart)
- [Microsoft Blazor Documentation](https://learn.microsoft.com/aspnet/core/blazor/)
- [.NET 9 Release Notes](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)

