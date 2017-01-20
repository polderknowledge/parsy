# Parsy Pattern Design Doc

Parsy

#Form

* Author: `Lorenzo Wallerlei, lorenzo@polderknowledge.nl`
* Date: `19-01-2017`
* Repository name: `Form`

## Goals

This document is the proposal for the form component, it describes what should go in a form and how a form should react 
to user input.

## References

http://getbootstrap.com/components/#input-groups

http://foundation.zurb.com/sites/docs/forms.html

http://webaim.org/techniques/forms/controls

## Requirements

- All the inputs within the form should contain a tab index.
- All the inputs should have error messages if there is some sort of validation on that specific input
- Inputs Must have labels
- Form must have an action attribute
- If there is a collection of inputs it must be surrounded by a fieldset.
- If you use an fieldset you must use a legend for it.

# Case studies `<Optional>`

Not applied.

## Existing implementations

https://www.tax.service.gov.uk/gg/sign-in?continue=%2Faccount&origin=unknown

What it does good.
- Form fields are described by labels.
- Flow of the tab indexes is natural.
- Clear error messages.
- Submits with the enter key.
- Has a form action so it could be submitted without the use of javascript.

What it could do better.
- Refocus after validation.

## Proof of concept

This pattern has no proof of concept. It is a set of rules to follow for making a good structured, valid and accessible
form.

## API

Not used.

## Constraints

TBD.

## Classes

    Name       | Type     | Description
    -----------|----------|-------------

    has-errors | "global" | Can make it easier for other componts to know if the form has errors.


## Accessibility `<Important>`

TBD.

### How to use the component with a keyboard only

This must be entirely usable with only the tab key.

### How a screen-reader user will interact with the component

- The screen reader reads all the labels of the form inputs
- If a input has a description, use aria-describedby so the screen reader can read the description.

### How the component will work without color

Not applicable.

### How the component will enforce any a11y requirements

I need some help with this point.

## Roadmap and timeline

Not applicable.

[this article]: https://www.polymer-project.org/0.5/articles/accessible-web-components.html
[Daltonize]: https://chrome.google.com/webstore/detail/chrome-daltonize/efeladnkafmoofnbagdbfaieabmejfcf
[SEE]: https://chrome.google.com/webstore/detail/see/dkihcccbkkakkbpikjmpnbamkgbjfdcn
[WAI-ARIA Authoring Practices doc]: https://www.polymer-project.org/0.5/articles/accessible-web-components.html
[codepen]: https://codepen.io