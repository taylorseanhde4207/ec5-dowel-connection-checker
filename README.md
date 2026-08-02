# EC5 Timber Dowel Connection v2026 - timber connection engineering analysis app

> **A browser-based EC5 analysis tool for timber dowel connections, with fastener-group load distribution, Johansen-style resistance checks, and utilization reporting in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/taylorseanhde4207/ec5-dowel-connection-checker?style=flat-square)](https://github.com/taylorseanhde4207/ec5-dowel-connection-checker)

---

<p align="center">
  <a href="https://taylorseanhde4207.github.io/ec5-dowel-connection-checker/">
    <img src="https://img.shields.io/badge/Download-EC5%20Timber%20Dowel%20Connection%20Latest-brightgreen?style=for-the-badge" alt="Download EC5 Timber Dowel Connection">
  </a>
</p>

> **[Download EC5 Timber Dowel Connection v2026](https://taylorseanhde4207.github.io/ec5-dowel-connection-checker/)**

---

[Download Latest Build](https://taylorseanhde4207.github.io/ec5-dowel-connection-checker/)

---

## Overview

EC5 Timber Dowel Connection provides browser-based support for designing and reviewing timber connections made with dowel-type fasteners. The application distributes axial force, shear, and moment through fastener groups, then assesses lateral resistance and utilization using EC5 and Johansen-style calculation methods.

It is intended for engineering workflows involving timber-timber and steel-timber connection arrangements. Users can create standard fastener grids or edit individual fastener coordinates, allowing the same tool to serve quick preliminary studies and closer examination of specific group layouts.

---

## Capabilities

- Calculates axial, shear, and moment effects for fastener groups
- Performs EC5/Johansen-style lateral resistance and yield-mode checks
- Handles timber-timber and steel-timber connection configurations
- Creates regular fastener grids and allows direct coordinate editing
- Reports force vectors, resultant forces, resistance, and utilization for each fastener
- Provides preliminary spacing, edge-distance, and steel-plate condition checks
- Produces printable PDF output using the browser print function
- Retains entered data between sessions through localStorage

---

## Getting Started

1. Clone or download the repository:
   - `git clone https://github.com/taylorseanhde4207/ec5-dowel-connection-checker.git
2. Run the project through a web server that can serve the application, or use the published site.
3. For local use, open the primary HTML file in a browser or serve the project directory with a lightweight static server.

Example local launch:
- `npx serve .`

---

## Using the Application

1. Choose the connection model and initial fastener arrangement.
2. Provide the connection geometry, material properties, and applied loads.
3. Keep the generated regular grid or modify fastener positions individually.
4. Examine the resulting force allocation, resistance values, and utilization results.
5. Open the browser print dialog whenever a PDF record is required.

A practical review sequence is:

- choose the connection type
- define the loads
- check the results for each fastener
- revise the arrangement if spacing or edge-distance checks require it
- print or export the completed report

---

## Stored Configuration

Application settings are entered through the interface and retained in browser localStorage.

Stored data can include:

- connection geometry
- fastener coordinates
- load values
- material and resistance parameters

Clearing browser storage removes previously saved entries, so those values will need to be entered again.

---

## Requirements

- A current web browser
- JavaScript enabled
- Browser local storage available for preserving inputs
- The application HTML files or access to the published web build

Recommended setup:

- A Chromium-, Firefox-, or Safari-class browser
- Enough display space to inspect result tables and layout checks

---

## Frequently Asked Questions

### How can I use the newest version?

Open the latest published build through the download link above, or update the local project files to the current repository version.

### Where does the application keep my input data?

The application saves inputs in your browser's localStorage.

### Is PDF printing supported?

Yes. Open the browser print dialog and select the option for creating a printable PDF.

### Why are my updates not visible?

Reload the application, check that browser storage is enabled, and confirm that you are modifying the active connection configuration.

### Which connection arrangements are available?

The application supports both timber-timber and steel-timber connections.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
