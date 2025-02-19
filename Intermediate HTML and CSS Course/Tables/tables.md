# HTML Tables

## Usage

Tables are used for *structuring tabular data* **exclusively**

**Shouldn't** use tables for pages' layouts which is bad for *accessibility*,
*responsiveness* and *maintainability*

### Syntax

#### HTML Elements

- `<table>`: used to open a new table, contains all the other HTML Elements below
- `<tr>`: used to add a row, contains all the other HTML Elements below
- `<th>`: used to create a table **header** (or *column title*)
- `<td>`: used to add a division to a row

#### Attributes

- **colspan**: defines how much element wide the column is going to be
  (eg: `<td colspan="3"></td>` is going to be three elements wide)
- **rowspan**: same behaviour as colspan but for rows
  (eg: `<td rowspan="3"></td>` is going to be three elements wide)

## Accessibility

If done well, tables can be interpreted by accessibility tools

## Styling
