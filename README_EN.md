# MINTO Basic
A lightweight visual catalog & viewer for hyperspectral data

The software "MINTO Basic" is a lightweight desktop application designed for researchers and engineers to quickly overview, intuitively browse, and organize their vast amounts of hyperspectral image data.
Developed to help you "keep an eye" on hyperspectral data that tends to get cluttered, this tool provides a clear thumbnail list view and seamless file management.

---

## Key Features

* **Automated Scanning and Cataloging of ENVI Formats**
  * Automatically searches for header files (`.hdr`) within a specified folder and registers metadata (resolution, wavelength range, number of bands, etc.) to the database.
* **Thumbnail List View and RGB Wavelength Customization**
  * Extracts representative wavelengths (R/G/B) from multi-band data to automatically generate thumbnail images. Supports customizing the RGB wavelength assignments.
* **Intuitive Search and Filtering**
  * Keyword search by filename, subject name, and memo content, as well as filtering to display only ★ favorited data.
* **Metadata and Attribute Information Entry**
  * Check detailed image information simply by selecting the data. Supports manual entry and saving of "Subject" labels and "Memo" text.

---

## System Requirements

* **Supported OS:** Windows 10 / 11 (64-bit)
* **Memory:** 8 GB or more recommended (depends on the size of the hyperspectral data being handled).
* **Display Resolution:** 
  - Minimum: 1280 × 720 (HD)
  - Recommended: 1920 × 1080 (Full HD) or higher
  *Note: We recommend using a Full HD or higher monitor to display both the thumbnail list table and the detailed information panel comfortably.

---

## Installation Guide

1. Download the latest `MINTO_Basic_**.msi` (or the `_EN` version) from the Releases page ( https://github.com/litandus-yako/MINTO_Basic/releases ).
2. Double-click the downloaded `.msi` file to launch the installer. If a Microsoft Defender SmartScreen warning appears, click [More info] -> [Run anyway] (at your own risk).
3. Follow the on-screen instructions to complete the installation.
4. Once installed, you can launch the app from the "MINTO Basic" desktop shortcut or the `.exe` file in the installation folder.

---

## Basic Usage

1. **Specifying the Search Folder**
   * Click the [📂 Select Folder] button at the top left of the window and select the directory containing your hyperspectral data (`.hdr`). A background scan will start automatically, and the data will be listed.
2. **Browsing and Searching Data**
   * Enter keywords in the search bar at the top right to filter data, or check the [★ Favorites Only] box to display only your starred items.
3. **Entering Detailed Information**
   * Select an item from the list to view a high-resolution thumbnail and image metadata in the detail panel on the bottom left. You can enter and save any text in the "Subject" and "Memo" fields.
4. **Opening Folders**
   * Click the [📁 Open] button in the table or double-click a row to directly open the file explorer to the directory where the target data is saved.

---

## For Users Requiring Advanced Features (Introducing MINTO Pro)

`MINTO Basic` is specialized as a lightweight, fast viewer with basic data organization functions (no future feature updates are planned for the Basic version).
If you require AI-based automatic classification, batch editing of massive datasets, or the ability to freely add custom labels, please consider our commercial version, `MINTO Pro` (currently in development).

**[Planned Features for MINTO Pro]**
* AI automatic classification of subjects using Machine Learning/Deep Learning (ResNet18 / SVM / Random Forest / k-means).
* Saving, loading, and cross-project sharing of classification models (`.pkl`).
* Free addition and deletion of common/individual custom labels (attribute fields).
* Bulk editing of "Favorites", "Subject Labels", and "AI Estimation Results" across multiple datasets.

---

## Third-Party Licenses

This application is built using open-source software including Python, PySide6, NumPy, Pillow, Spectral, and others. Please refer to the `THIRD_PARTY_LICENSES.md` file in the installation directory for the full text of copyrights and licenses for each library.

---

## Inquiries / Bug Reports

Please submit bug reports and feature requests via GitHub [Issues] or the LITANDUS Website contact form ( https://sites.google.com/litandus.com/litandus/contact ).
