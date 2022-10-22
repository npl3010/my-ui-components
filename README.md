# LEARNING:

## CSS - Units:
- fr.

## CSS - Grid:

### 1. Properties:
```
display: grid;
gap: __;
```

```
grid-template-rows: __;
grid-template-columns: __;
```
- Examples:
  - grid-template-columns: 100px 200px 300px;
  - grid-template-columns: 50px 100%;
  - grid-template-columns: 1fr 1fr 1fr;
  - grid-template-columns: 100px auto;

```
grid-template-areas: __;
```
- Examples:
  - grid-template-areas:
      'header header header'
      'menu main main'
      'menu footer footer';
    - The values "header", "menu", "main", "footer" are all specified by user.

```
grid-row: __;
grid-column: __;
```
- Notes:
  - grid-column: is a shorthand property for: grid-row-start, grid-row-end.
  - grid-row: is a shorthand property for: grid-column-start, grid-column-end.
- Examples:
  - grid-column: 1 / 3;
  - grid-column: 1 / span 2;
    - This is the same as "grid-column: 1 / 3;".

```
grid-area: __;
```
- Examples:
  - grid-area: header;
    - The values "header" is predefined by user.

### 2. Others:
- Grid track (track line):
  - Start from 1 (left to right).
  - Start from -1 (right to left).
  - Number of tracks = (number of columns + 1).
  - A track line bettween two columns is called "column line".
  - A track line bettween two rows is called "row line".

## CSS - 2D/3D Transforms:

### 1. Properties:
```
perspective: __;
perspective-origin: __;
transform: __;
transform-origin: __;
transform-style: __;
```


# COMPONENTS:

## Image grid.

## Parallax.
