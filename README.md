# tables https://accessiblu.github.io/tables/
Examples of accessible tables
Tables can be navigated by screen reader users similarly to how a spreadsheet is navigated, from cell to cell and in any direction. When coded properly, the headers that correspond to each data cell can be conveyed when screen reader users land on a data cell, making the table more understandable. This will only work, though, if the table is marked up appropriately in the code. Here are some essential rules for coding tables:

Tables should be represented using the <table> element.
Tables should have a programmatically associated name, preferably through the <caption> element.
Table headers must be designated using the <th> element.
Table data cells must be associated with their header cells using scope="col" for column headers and scope="row" for row headers.
Grouped (or merged) table header cells must be associated with their data cell groups, preferably scope="colgroup" for grouped column headers and scope="rowgroup" for grouped row headers.
For complex tables, if <th> and scope is not effective in associating header and data cells, then id must be used on the <th> element and headers used on the <td> elements.
