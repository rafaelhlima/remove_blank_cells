# Remove Blank Cells

This is an extension for LibreOffice Calc that removes blank cells in various situations, such as single columns and single rows, as well as tables with multiple columns and rows.

This extension is still in Beta stage, so bugs are expected. If anything goes wrong, please report an issue.

## Installation

To install this extension:

1) Download the [Latest OXT file](Releases/RBCells_0-9.oxt)
2) On any LibreOffice component, go to **Tools > Extensions Manager...**
3) Click **Add** and chose the OXT file
4) Click **OK** and Accept the licence to finish installation

## Usage

This extension provides 5 different use cases for removing blank cells as described below. The extension decides what will be done based on the current selection in the active sheet.

### Remove Blanks in a Single Column

When you select a single column, the extension removes all blank cells placing cells with contents to the top of the selected range.

![](GIFs/Single_Column.gif)

### Remove Blanks in a Single Row

When you select a single row, the extension removes all blank cells placing cells with contents to the left side of the selected range.

![](GIFs/Single_Row.gif)

### Remove Blanks Rows in a Table

When you select a range with multiple rows and columns (a table), the extension will show a dialog box for you to decide what shall be done with the data.

If you select *Remove all blank rows*, then all rows with contents will be moved to the top of the selected range.

![](GIFs/RB_Rows.gif)

### Remove Blanks Columns in a Table

If you select *Remove all blank columns*, then all columns with contents will be moved to the left side of the selected range.

![](GIFs/RB_Columns.gif)

### Compact Data

This is still an experimental feature. If you select *Remove all blank cells (compact data)*, then all cells with contents will be compacted to the upper-left corner of the selected range.

![](GIFs/RB_Compact.gif)

## Compatibility

This extension was developed using LibreOffice 7.0. However, it should be compatible with LO 6.x onwards.

All screenshots, GIFs and files were created using Kubuntu 20.10.
