# Creating Waterfall Charts in Blazor for Financial and Business Analysis

Build interactive waterfall charts in Blazor to visualize financial data flows, revenue breakdowns, and business metrics using Blazor Charts.

## Overview

This sample demonstrates how to create professional waterfall charts in Blazor applications using Blazor Charts component. Waterfall charts are ideal for visualizing cumulative effects of sequential financial data, showing how an initial value is affected by a series of positive or negative values.

## Features

- **Waterfall Chart Visualization** - Display financial flows with positive and negative values to show how revenue transforms through various business operations
- **Interactive Tooltips** - Hover over chart elements to reveal detailed value information with formatted currency display
- **Intermediate Sums** - Mark and highlight cumulative breakpoints in the chart (such as Gross Profit calculations)
- **Final Totals** - Emphasize end calculations and summary values (such as Net Profit)
- **Responsive Design** - Charts automatically adapt and scale to different screen sizes and device orientations
- **Bootstrap Theming** - Professional appearance with Bootstrap 5 styling integration
- **Data Labels** - Display values directly on chart bars for immediate readability


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

## Key Components

### Home.razor
The main page containing the waterfall chart implementation. It demonstrates:
- Creating a waterfall chart with Syncfusion's `SfChart` component
- Configuring chart series with `ChartSeries` of type `Waterfall`
- Setting up primary X and Y axes
- Adding tooltips and data labels
- Defining intermediate and final sum points

## Resources

- [Waterfall Chart Guide](https://blazor.syncfusion.com/documentation/chart/chart-types/waterfall)
- [Waterfall Chart Definition, Use Cases, and Anatomy](https://www.visualizing.org/waterfall-chart)


