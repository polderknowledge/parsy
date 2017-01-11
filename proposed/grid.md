# Grid

- Author: `Jaap van Otterdijk <jaap@polderknowledge.nl>`
- Date: `11-01-2017`
- Repository name: polderknowledge/parsy-grid

## Goals
The grid pattern can be used to organize other components in columns and rows. This pattern
is responsive and allows the developer to organize the components per screen size.

A grid consist out of 2 different elements:
- row
- column

A column can only be positioned in a row. 

## References
- [A standalone flexbox example.][reference-flexboxgrid]
- [Bootstrap has an implementation][reference-bootstrap]
- [Foundation has an implementation][reference-foundation]

## Requirements

- A grid MUST only contain positioning styling. No colors or other visible styling.
- It MUST be possible to nest grids
- A grid SHALL be based on column sizes from 1 to 12.
- A `row` CAN contain one or more columns as long the fit in the maximum size of 12
- A `row` MUST align its columns from left to right.
- A `column` CAN contain as many elements as the developer demands.
- A `column` CAN have multiple sizes depending on the screen size from 1 to 12.
- A `column` CAN have a offset depending on the size of the screen from 1 to 11 to push the column x positions to left.

# Case studies `<Optional>`
<TDB>

## Existing implementations
<TDB>

## Proof of concept
<TDB>

## API
<TDB>

## Constraints
The components `row`, `column` and `box` can only be applied on elements with display type `box`

## Classes
<TDB>

## Accessibility `<Important>`

The component will resize according the size of the device' screen. No other user
interaction is required. So this component will not have much influence on the accessibility.

### How to use the component with a keyboard only
Not applicable. Since there is no user interaction required.

### How a screen-reader user will interact with the component
The component will work out of the box with a screen reader.
    
### How the component will work without color
Not applicable.

### How the component will enforce any a11y requirements
Not applicable.

## Roadmap and timeline
Talk about how the work can be split up into different milestones and the timing for completion.

[reference-flexboxgrid]: http://flexboxgrid.com/
[reference-bootstrap]: https://getbootstrap.com/examples/grid/
[reference-foundation]: http://foundation.zurb.com/grid.html
