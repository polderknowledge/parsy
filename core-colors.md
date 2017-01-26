# Parsy Pattern Design Doc

> HOW TO USE THIS TEMPLATE
> Fill in the parts that are relevant. Not all sections are going to apply to every component.

Parsy

# <Component Name>

* Author: `Lorenzo Wallerlei lorenzo@polderknowledge.nl`
* Date: `26-01-2017`
* Repository name: `Core Colors`

## Goals

Core colors will be a core component where other components and patterns will be based on, the user can use these colors to create a
consistent color representation in the component that is being created. Through this way we can create a consistent use 
of colors throughout the library. It will house the colors like brand color, primary color, 
success color and danger color. 

## References

[http://getbootstrap.com/components/#alerts]
[http://getbootstrap.com/components/#btn-dropdowns]
In the above 2 links you can see how bootstrap manages to keep te same color patterns on 2 different component. This 
is exactly what needs to be achieved.

## Requirements

- These colors MUST be put in easy to use variables.
- For each color defined there MUST be a corresponding class, for example the class could be placed on a component to 
emphasize the component is in a certain state.

- Core settings variables SHOULD not be overwritten.

# Case studies `<Optional>`

Almost every pattern library uses this kind of system to keep coloring consistent throughout an application.

## Existing implementations

[http://getbootstrap.com/]
[https://foundation.zurb.com/sites/docs/global.html#colors]

## Proof of concept

Can not be applied yet.

## API

Not yet defined

## Constraints

There are no constraints.

## Classes

Name | Type | Description
------|------|-------------
left | "position" | Will align the component to the left.
open | "state" | Whether the example is opened or closed.

## Accessibility `<Important>`

Not applied.

### How to use the component with a keyboard only

You don't have to

### How a screen-reader user will interact with the component

Not applied.

### How the component will work without color

The end user should be able to choose default colors he want throughout the library.

### How the component will enforce any a11y requirements

Not applied.

## Roadmap and timeline

ASAP

[this article]: https://www.polymer-project.org/0.5/articles/accessible-web-components.html
[Daltonize]: https://chrome.google.com/webstore/detail/chrome-daltonize/efeladnkafmoofnbagdbfaieabmejfcf
[SEE]: https://chrome.google.com/webstore/detail/see/dkihcccbkkakkbpikjmpnbamkgbjfdcn
[WAI-ARIA Authoring Practices doc]: https://www.polymer-project.org/0.5/articles/accessible-web-components.html
[codepen]: https://codepen.io
