# IDF File Batch Modification Tool

This repository contains an HTML tool for generating IDF (Input Data File) files in a batch manner.

## Overview

The tool allows you to select an existing IDF file, specify a material name, as well as the values of Solar Absorptance and Visible Absorptance. Based on these parameters, the tool will generate IDF files with the applied changes while preserving the original structure and content.

## Usage Instructions

1. Select an existing IDF file by clicking the "File" button and choosing the desired file.
2. Enter the material name in the "Material Name" field.
3. Enter the Solar Absorptance values in the "Solar Absorptance" field, separated by commas. Example: `0.7, 0.8, 0.9`.
4. Enter the Visible Absorptance values in the "Visible Absorptance" field, separated by commas. Example: `0.5, 0.6, 0.7`.
5. Click the "Generate Files" button to start the processing.
6. The resulting IDF files will be automatically downloaded.

## Notes

- Ensure that you select a valid IDF file following the naming convention `XXX-YYY-00-R00.idf`.
- The Solar Absorptance and Visible Absorptance values should have the same number of elements.
- The tool preserves the original structure of the IDF file and only replaces the values of the specified material.

## Technologies Used

- HTML
- CSS
- JavaScript

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute this code, as long as you maintain the reference to the original author.

---

Developed by Gabriel Amaro. All rights reserved.
