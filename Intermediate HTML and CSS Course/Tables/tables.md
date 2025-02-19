# HTML Tables

## Usage

Tables are used for *structuring tabular data* **exclusively**

**Shouldn't** use tables for pages' layouts which is bad for *accessibility*,
*responsiveness* and *maintainability*

### Syntax

#### HTML Elements

- `<table>`: used to open a new table, contains all the other HTML Elements below
- `<thead>`: wrap the header elements
- `<tbody>`: wrap the content of the table excluding the header and footer
  note that it will be automatically included by the browser if not added
- `<tfooter>`: wrap the footer of the table
- `<tr>`: used to add a row, contains all the other HTML Elements below
- `<th>`: used to create a table **header** (or *column title*)
- `<td>`: used to add a division to a row
- `<colgroup>` and `<col>`: at the top of the table Element, used to define
  a group of column

#### Attributes

- **colspan**: defines how much element wide the column is going to be
  (eg: `<td colspan="3"></td>` is going to be three elements wide)
- **rowspan**: same behaviour as colspan but for rows
  (eg: `<td rowspan="3"></td>` is going to be three elements wide)

## Accessibility

If done well, tables can be interpreted by accessibility tools

**Screen Readers** will use HTML Elements such as `th` to identify and interpret
informations in the table

Other html elements are provided to make the table even more accessible.

### HTML Elements and attributes for accessibility

- `<caption>`: This element is placed at the top of the table element and
  used by the reader to provide a description of the table to the user
*Note: `<summary>` is also available but deprecated*

- **scope**: place as an attribute of `<th>` to tell the screen reader
  what the header is referring to (*row*, *col*, *rowgroup* or *colgroup*), the reader
  can then read the whole row/column/colgroup/rowgroup to the user

Alternatively, **id** coupled with **header** attributes can be used to help
the reader connect a header with elements in the table
