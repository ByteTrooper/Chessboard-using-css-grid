# Chessboard-using-css-grid
This chessboard is implemented using CSS Grid layout. The `.container` div serves as the grid container, and it is given a fixed width of 800 pixels (`width: 800px`) to ensure a specific size for the chessboard.

The container is displayed as a grid with `display: grid`, and the background color is set to `darkgrey` with a border of `1px` solid black. The grid-template-columns and grid-template-rows properties are set to `repeat(8, 1fr)`, indicating that there are 8 equal-sized columns and rows in the grid.

Each square on the chessboard is represented by a `div` element with either the class `.white` or `.black`. The `.white` squares have a background color of `#f0d9b5`, while the `.black` squares have a background color of `#b58863`. Both squares have a height and width of `100px`.

By setting `grid-gap: 0`, any gaps between the grid cells are eliminated, resulting in a seamless chessboard appearance without any spacing between the squares.

Overall, this implementation provides a visually appealing chessboard layout using CSS Grid, allowing for easy customization and flexibility in terms of sizing, styling, and responsiveness.
