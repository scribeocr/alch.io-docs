---
layout: default
title: Layout Controls
nav_order: 4
---

# Edit Table Layout

### Adding and Modifying Tables
- Add table.
	- Add a table by clicking the `Add Data Table` button and selecting the area where the table should be inserted.
- Delete table.
	- Delete a table by selecting the entire table (including all columns), right clicking, and selecting `Delete Table`.
- Resize table.
	- A table can be resized by dragging the controls that appear when the table is selected.
		- When the table is resized to exclude a column, that column is automatically deleted.

### Adding and Modifying Columns
- Adjusting column bounds.
	- Column boundaries can be adjusted by clicking the column separator and dragging it to the left or right.
- Combining columns.
	- Neighboring columns can be combined by selecting the columns, right clicking, and selecting `Combine Columns` from the context menu.
- Splitting columns.
	- A single column can be split into multiple columns by selecting the column, right clicking, and selecting `Split Column` from the context menu.
- Adding/deleting columns.
	- There are no "add column" or "delete column" buttons.
	- Columns can be added/deleted through a combination of resizing the table, and splitting/combining existing columns.
		- When the table is resized to exclude a column, that column is automatically deleted.

### Set Default Page Layout
It is possible to set a default layout, which will be applied to all pages where tables where pages have not been edited manually.  Setting a default makes it easy to process documents such as invoices or reports, where 50 pages may contain the same layout. 

1. To make the layout from the current page the default, click `Save As Default`.
2. To discard all edits made to an individual page, reverting it to the default, click `Revert To Default`.

# Text Assignment to Columns
By default, individual words are assigned to the column they overlap the most with.  While this behavior is generally correct, users can modify how words are assigned to columns by right clicking column(s) and selecting options in the `Overlap Rules` drop-down menu.  Specifically, the following properties can be modified.

- Is text assigned to columns on a word-by-word basis, or should entire lines be assigned to columns?
	- Select `word` to assign text to column by word; select `line` to assign entire lines to the same column.
- Is text assigned to columns based on where the text starts, or based on where the majority of the text is found?
	- Select `left` to assign text to the column where the text starts; select `majority` to assign text to the column it overlaps the most with.

# Downloading Data
To download tables in a tabular format, navigate to the `Download` tab, and then set the format to `.xlsx`.  Excel (`.xlsx`) is currently the only supported format for writing tabular data.