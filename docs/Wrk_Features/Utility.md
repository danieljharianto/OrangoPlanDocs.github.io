---
hide:
  # - navigation
  - toc
---

##Utility
Utility Tools support data handling, interoperability, and workflow management across the modeling environment. The tools are divided into six categories: File I/O, for importing and exporting data; Data Preview and Manipulation, for inspecting, cleaning, and transforming datasets; Data Classification, for organizing data into meaningful groups; Rhino Reference, for linking and managing Rhino geometry; List Matching, for aligning and synchronizing datasets; and Object Attributes, for editing and managing geometric and non-geometric attributes.


### File I/O



<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #e8e8e8;">
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Tool</th>
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Function</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Input</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Output</th>
    </tr>
    <tr style="background-color: #e8e8e8;">
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- CSV Import -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Import_CSV.png" alt="CSV Import" style="height:25px; margin-bottom:5px;">
          <span>CSV Import</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Import CSV File</td>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">File</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">File Path</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Path to the CSV file</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers as a list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">CSV data organized as a tree (columns as branches)</td>
    </tr>

    <!-- CSV Export -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Export_CSV.png" alt="CSV Export" style="height:25px; margin-bottom:5px;">
          <span>CSV Export</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Export as CSV File</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Column headers for CSV</td>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Stat</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Status</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Export status message</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data to export as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Path</td>
      <td style="padding:12px; border:1px solid #ddd;">File Path</td>
      <td style="padding:12px; border:1px solid #ddd;">File path to export</td>
    </tr>

    <!-- XLS Import -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Import_XLS.png" alt="XLS Import" style="height:25px; margin-bottom:5px;">
          <span>XLS Import</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Import XLS File</td>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">File</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">File Path</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Path to the CSV file</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers as a list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">CSV data organized as a tree (columns as branches)</td>
    </tr>

    <!-- XLS Export -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Export_XLS.png" alt="XLS Export" style="height:25px; margin-bottom:5px;">
          <span>XLS Export</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Export as XLS File</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Column headers for CSV</td>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Stat</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Status</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Export status message</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data to export as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Path</td>
      <td style="padding:12px; border:1px solid #ddd;">File Path</td>
      <td style="padding:12px; border:1px solid #ddd;">File path to export</td>
    </tr>
  </tbody>
</table>

!!! Tip  "Important Tips"

    - Ensure all input files follow the required format, structure, and encoding (e.g., consistent delimiters, headers, and data types).
    - Verify coordinate systems, units, and scale before importing to avoid misalignment or incorrect calculations.
    - Clean and validate datasets in advance by removing null values, duplicates, or inconsistent entries.
    - When exporting data, clearly define attribute fields and naming conventions to maintain compatibility with GIS, CAD, or external analysis tools.
    - Use incremental exports during iterative workflows to track changes and simplify troubleshooting.
    - Always cross-check imported and exported data against the source files to confirm accuracy and completeness.
    
### Data Preview & Manipulation

<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #e8e8e8;">
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Tool</th>
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Function</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Input</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Output</th>
    </tr>
    <tr style="background-color: #e8e8e8;">
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- Table Preview -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Table_Preview.png" alt="Table Preview" style="height:25px; margin-bottom:5px;">
          <span>Table Preview</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Preview CSV or XLS File</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Column headers for CSV</td>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Prev</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Formatted Preview</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Formatted CSV preview with padding</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data to export as a tree</td>
    </tr>

    <!-- Column Add -->
    <tr>
      <td rowspan="4" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Add Column.png" alt="Column Add" style="height:25px; margin-bottom:5px;">
          <span>Column Add</span>
        </div>
      </td>
      <td rowspan="4" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Add new column in data tree</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Bh</td>
      <td style="padding:12px; border:1px solid #ddd;">Base Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers of the base CSV</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Uh</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Combined headers of the updated CSV</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Bd</td>
      <td style="padding:12px; border:1px solid #ddd;">Base Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data tree of the base CSV</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ud</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated CSV data as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Nh</td>
      <td style="padding:12px; border:1px solid #ddd;">New Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers of the new columns</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Nd</td>
      <td style="padding:12px; border:1px solid #ddd;">New Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data tree of the new columns</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Column Remove -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Remove Column.png" alt="Column Remove" style="height:25px; margin-bottom:5px;">
          <span>Column Remove</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Remove column in data tree</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">List of CSV headers</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Uh</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated headers</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">CSV data organized as a tree (columns as branches)</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ud</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated CSV data as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Rh</td>
      <td style="padding:12px; border:1px solid #ddd;">Header to Remove</td>
      <td style="padding:12px; border:1px solid #ddd;">Header of the column to remove</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Pivot by Header -->
    <tr>
      <td rowspan="5" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Pivot_By_Header.png" alt="Pivot by Header" style="height:25px; margin-bottom:5px;">
          <span>Pivot by Header</span>
        </div>
      </td>
      <td rowspan="5" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Pivot data by a specific column header</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data as tree</td>
      <td rowspan="5" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Group</td>
      <td rowspan="5" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Grouped Data</td>
      <td rowspan="5" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Grouped data as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Key</td>
      <td style="padding:12px; border:1px solid #ddd;">Group Key</td>
      <td style="padding:12px; border:1px solid #ddd;">Name of the header to use for grouping key</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Value Column</td>
      <td style="padding:12px; border:1px solid #ddd;">Name of the header to extract values from</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Remove Header</td>
      <td style="padding:12px; border:1px solid #ddd;">Remove header values in each group</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Dups</td>
      <td style="padding:12px; border:1px solid #ddd;">Dremove Duplicates</td>
      <td style="padding:12px; border:1px solid #ddd;">Remove duplicate values in each group</td>
    </tr>
  </tbody>
</table>

### Data Classification

<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #e8e8e8;">
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Tool</th>
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Function</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Input</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Output</th>
    </tr>
    <tr style="background-color: #e8e8e8;">
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- Interval Classifier -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Interval Classifier.png" alt="Interval Classifier" style="height:25px; margin-bottom:5px;">
          <span>Interval Classifier</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Divides numeric data into equal-width interval</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">N</td>
      <td style="padding:12px; border:1px solid #ddd;">Numbers</td>
      <td style="padding:12px; border:1px solid #ddd;">List of values to classify</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Max</td>
      <td style="padding:12px; border:1px solid #ddd;">Max</td>
      <td style="padding:12px; border:1px solid #ddd;">Maximum value in list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">n</td>
      <td style="padding:12px; border:1px solid #ddd;">Interval Segments</td>
      <td style="padding:12px; border:1px solid #ddd;">Number of interval division</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Min</td>
      <td style="padding:12px; border:1px solid #ddd;">Min</td>
      <td style="padding:12px; border:1px solid #ddd;">Minimum value in list</td>
    </tr>
    <tr>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">I</td>
      <td style="padding:12px; border:1px solid #ddd;">Intervals</td>
      <td style="padding:12px; border:1px solid #ddd;">List of numeric interval strings</td>
    </tr>
  </tbody>
</table>

### Rhino Reference

<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #e8e8e8;">
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Tool</th>
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Function</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Input</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Output</th>
    </tr>
    <tr style="background-color: #e8e8e8;">
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- Reference by Layer -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Reference_By_Layer.png" alt="Reference by Layer" style="height:25px; margin-bottom:5px;">
          <span>Ref Layer</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Reference Rhino object by its layer</td>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">L</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Input Layer</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Layer name to query</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Obj</td>
      <td style="padding:12px; border:1px solid #ddd;">Objects</td>
      <td style="padding:12px; border:1px solid #ddd;">Objects from layer</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ref</td>
      <td style="padding:12px; border:1px solid #ddd;">Referenced Layer</td>
      <td style="padding:12px; border:1px solid #ddd;">Object's layer name and path</td>
    </tr>

    <!-- Reference by Color -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Reference_By_Color.png" alt="Reference by Color" style="height:25px; margin-bottom:5px;">
          <span>Ref Color</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Reference Rhino object by its color</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Color</td>
      <td style="padding:12px; border:1px solid #ddd;">Target color to match</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Obj</td>
      <td style="padding:12px; border:1px solid #ddd;">Objects from layer</td>
      <td style="padding:12px; border:1px solid #ddd;">Objects from matching color</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">T</td>
      <td style="padding:12px; border:1px solid #ddd;">Tolerance</td>
      <td style="padding:12px; border:1px solid #ddd;">Color matching tolerance</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Idx</td>
      <td style="padding:12px; border:1px solid #ddd;">Index</td>
      <td style="padding:12px; border:1px solid #ddd;">Index of matching color</td>
    </tr>
  </tbody>
</table>

### List Matching

<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #e8e8e8;">
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Tool</th>
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Function</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Input</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Output</th>
    </tr>
    <tr style="background-color: #e8e8e8;">
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- Match List Geo -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Match_List_Geometry.png" alt="Match List Geo" style="height:25px; margin-bottom:5px;">
          <span>Match List Geo</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Match text tree against a mask list text</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Text</td>
      <td style="padding:12px; border:1px solid #ddd;">Text Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of input text</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Bool</td>
      <td style="padding:12px; border:1px solid #ddd;">Boolean tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Boolean tree result</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Mask</td>
      <td style="padding:12px; border:1px solid #ddd;">Mask List</td>
      <td style="padding:12px; border:1px solid #ddd;">List of match strings</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Matched Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Matched Tree Result</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of dispatched items basd on match list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">M</td>
      <td style="padding:12px; border:1px solid #ddd;">Matches List</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree to dispatch using masking</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Match List Text -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Match_List_Text.png" alt="Match List Text" style="height:25px; margin-bottom:5px;">
          <span>Match List Text</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Match text tree against a mask list text</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Text</td>
      <td style="padding:12px; border:1px solid #ddd;">Text Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of input text</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Bool</td>
      <td style="padding:12px; border:1px solid #ddd;">Boolean Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of boolean match mask results</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Mask</td>
      <td style="padding:12px; border:1px solid #ddd;">Mask List</td>
      <td style="padding:12px; border:1px solid #ddd;">List of match mask strings</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Matched Values</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of dispatched items based on match list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">M</td>
      <td style="padding:12px; border:1px solid #ddd;">Matches List</td>
      <td style="padding:12px; border:1px solid #ddd;">List to dispatch using masking results</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
  </tbody>
</table>

### Object Attributes

<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #e8e8e8;">
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Tool</th>
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Function</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Input</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Output</th>
    </tr>
    <tr style="background-color: #e8e8e8;">
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- Extract Object Attributes -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Extract_Object_Attributes.png" alt="Extract Object Attributes" style="height:25px; margin-bottom:5px;">
          <span>Extract Attributes</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Extracts object attribute key–value pairs from referenced Rhino object</td>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">G</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Geometry</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Referenced geometry from Rhino</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Key</td>
      <td style="padding:12px; border:1px solid #ddd;">Keys</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute keys</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Values</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute values</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ref</td>
      <td style="padding:12px; border:1px solid #ddd;">Referenced Layer</td>
      <td style="padding:12px; border:1px solid #ddd;">Object's layer name</td>
    </tr>

    <!-- Edit Object Attributes -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Edit_Object_Attributes.png" alt="Edit Object Attributes" style="height:25px; margin-bottom:5px;">
          <span>Edit Attributes</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Edits object attributes key–value pairs to a referenced Rhino object</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">G</td>
      <td style="padding:12px; border:1px solid #ddd;">Geometry</td>
      <td style="padding:12px; border:1px solid #ddd;">Referenced geometry from rhino</td>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Stat</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Status</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Operation status message</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Key</td>
      <td style="padding:12px; border:1px solid #ddd;">Keys</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute keys</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Values</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute values</td>
    </tr>
  </tbody>
</table>

