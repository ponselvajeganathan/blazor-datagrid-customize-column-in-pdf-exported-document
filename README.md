# Customize Column Width in Blazor DataGrid PDF Export

## Overview

This sample demonstrates how to customize column widths in a PDF document exported from the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid). The implementation modifies export output by configuring the `Columns` collection of `PdfExportProperties` before the PDF export operation is executed. This approach allows the exported PDF document to use widths that differ from the widths displayed in the DataGrid UI, ensuring better readability and layout control in generated reports. The sample provides a practical reference for developers who need to adjust exported PDF formatting without affecting the on-screen DataGrid presentation.

## Key Features

- Demonstrates PDF export functionality in the Syncfusion Blazor DataGrid.
- Uses the `PdfExportProperties` class to customize export behavior.
- Configures the `Columns` property of `PdfExportProperties` to modify exported column widths.
- Allows exported PDF columns to use different dimensions than the corresponding DataGrid columns.
- Demonstrates export-time document customization without altering the DataGrid UI layout.
- Provides a reference implementation for tailoring PDF document formatting generated from DataGrid data.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file `Customize-PDFExportedColumn.sln`.
3. Restore all NuGet packages.
4. Set the `Customize_PDFExportedColumn` project as the startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
cd Customize_PDFExportedColumn
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `Customize_PDFExportedColumn/Pages/` — hosts the page that renders the Syncfusion DataGrid and executes the PDF export operation.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid PDF Export documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/pdf-export

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
