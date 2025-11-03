# List Comparison Tool

A lightweight, browser-based tool for comparing and analyzing differences between multiple lists of text data. Quickly find common items, unique entries, and perform various set operations with an intuitive interface.

![Screenshot](screenshot.png)

## 🚀 Quick Start

1. **Paste your first list** into the List A text area
2. **Paste your second list** into the List B text area  
3. **Choose your desired Comparison Mode**
4. **Click the Compare Lists button**

## ✨ Core Features

- **Data Input**: Paste directly into text areas or use the "Choose File" button to load data from `.txt` or `.csv` files
- **Multiple Lists**: Add up to 4 lists using the "+ Add Another List" button
- **Flexible Comparison**: Run comparisons across all active lists with global options
- **Dynamic Interface**: Remove additional lists using the × button that appears for lists C and D

## 🔍 Comparison Modes

### 2 List Comparison
- **In Both (A ∩ B)**: Items that exist in both List A and List B
- **All Distinct (A ∪ B)**: Every unique item from both lists combined
- **Only in B (B – A)**: Items in List B but not in List A
- **Only in A (A – B)**: Items in List A but not in List B
- **Unique to each (A ∆ B)**: Items in either A or B, but not both

### 3-4 List Comparison  
- **Intersection (In ALL lists)**: Items that exist in every single list
- **Union (All distinct items)**: Every unique item from all lists combined

## 🧹 Data Cleaning & Processing

### Pre-processing Options
- **Trim Whitespace**: Removes spaces from beginning/end of each line *(Default: On)*
- **Remove Empty Lines**: Filters out any blank lines *(Default: On)*  
- **Remove Duplicate Lines**: De-duplicates each list before comparison *(Default: Off)*

### Find & Replace
- **Per-List**: Each list has its own Find/Replace tool with regex support
- **Global**: Apply Find/Replace operations to all lists simultaneously using the "Apply to All Lists" option in List A

## ⚡ Advanced Features

- **CSV Column Selection**: When uploading multi-column CSV files, select which column to use for comparison
- **Enhanced Results (2 Lists Only)**:
  - Statistics box with item counts
  - Visual Venn diagram
  - Diff View showing added (+) and removed (-) lines with color coding

## ⚠️ Limitations

- **Text Area Size**: Very large lists (200KB+) may cause browser slowdowns - use file upload for large datasets
- **List Limit**: Maximum of 4 lists supported for optimal performance and clean layout

---

*Simple, fast list comparison directly in your browser - no installation required.*
