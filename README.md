# my-ui-components


# LEARNING:
## Notes - Units:
> fr.


## Notes - Properties:
> display: grid;

> grid-template-columns: __;
- grid-template-columns: 100px 200px 300px;
- grid-template-columns: 50px 100%;
- grid-template-columns: 1fr 1fr 1fr;
- grid-template-columns: 100px auto;

> grid-template-rows: __;

> gap: __;

> grid-column: __;

Is a shorthand property for: grid-column-start, grid-column-end.

- grid-column: 1 / 3;
- grid-column: 1 / span 2; // This is the same as "grid-column: 1 / 3;".

> grid-row: __;

Is a shorthand property for: grid-row-start, grid-row-end.

> grid-template-areas: __;
- grid-template-areas:
    'header header header'
    'menu main main'
    'menu footer footer';

> grid-area: __;
- grid-area: header;


## Others:
> Grid track (track line):
- Start from 1 (left to right).
- Start from -1 (right to left).
- Number of tracks = (number of columns + 1).
- A track line bettween two columns is called "column line".
- A track line bettween two rows is called "row line".


# COMPONENTS:
## Image grid.
