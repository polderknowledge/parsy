# Panel

* Author: `Walter Tamboer <walter@tamboer.nl>`
* Date: `18-12-2016`
* Repository name: `polderknowledge/parsy-panel`

## Goals

The panel pattern can be used to group content together. A page could contain 
multiple panels. A panel is a section on a page that can be used to identify 
content, it exists out of three parts:

1. A header (which is optional).
2. A body
3. A footer (which is optional)

The body contains the content of the panel, the optional header can be used to add an 
title to the content and the optional footer can be used to put secondary text
and/or buttons.

## References
- [The Bootstrap library has an implementation of panels.][reference-bootstrap]
- [The Foundation library has an implementation of panels.][reference-foundation]
- [JIRA has an implementation of what I call panels on its dashboard][reference-jira]

## Requirements

- It MUST be possible to style the component in any way one likes.
- The panel component MUST at least have a body section.
- The panel component MAY HAVE an optional header section.
- It MUST be possible to add options to the panel header. This way it becomes 
possible to add tabs or icons on the right side of the panel header.
- The panel component MAY HAVE an optional footer section.
- The component is a static component so no interaction is required.

# Case studies

A great example can be seen in the [template called Avant][avant-panels]. It's
clearly visible how each example is wrapped in a panel. It also shows why options
could be useful in the panel header. The Avant examples show an icon and tabs.

## Existing implementations

The best implementation I've found is the one from [Bootstrap][reference-bootstrap].
It has implemented the header, body and footer like described in this proposal.

## Proof of concept

* https://codepen.io/waltertamboer/pen/PbVobj

## API

Talk primarily about the public API of the components (both in templates and in 
component code). The following is an example API format that you can re-use.

## Constraints

There are no additional constraints for this component.

## Classes

Name            | Description
----------------|-------------------------------------------------------------
panel-container | The wrapper for a panel.
panel-header    | The class that defines a panel header.
panel-options   | The class that defines options that can be used in a header.
panel-body      | The class that defines the panel body.
panel-footer    | The class that defines a panel footer.

## Accessibility

The component will resize according the size of the device' screen. The options
that can be part of the header should be handled separately. On small devices 
these options might not be visible correctly but this should be investigated.

### How to use the component with a keyboard only

The only input this component has is the optional buttons or tabs that are placed
in the panel options. When they are present, they should have an according tabindex.

### How a screen-reader user will interact with the component

The component will work out of the box with a screen reader.

### How the component will work without color

* The panel header should have a bigger font size than the panel body.
* The panel footer should have a smaller font size than the panel body.

### How the component will enforce any a11y requirements

No additional comments here.

## Roadmap

No idea what to add here :)

[this article]: https://www.polymer-project.org/0.5/articles/accessible-web-components.html
[Daltonize]: https://chrome.google.com/webstore/detail/chrome-daltonize/efeladnkafmoofnbagdbfaieabmejfcf
[SEE]: https://chrome.google.com/webstore/detail/see/dkihcccbkkakkbpikjmpnbamkgbjfdcn
[WAI-ARIA Authoring Practices doc]: https://www.polymer-project.org/0.5/articles/accessible-web-components.html
[reference-bootstrap]: https://getbootstrap.com/components/#panels
[reference-foundation]: http://foundation.zurb.com/sites/docs/v/5.5.3/components/panels.html
[reference-jira]: https://jira.atlassian.com/secure/Dashboard.jspa
[avant-panels]: http://avant.redteamux.com/ui-panels.php
