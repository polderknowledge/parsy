# Parsy Pattern Design Doc

> HOW TO USE THIS TEMPLATE
> Fill in the parts that are relevant. Not all sections are going to apply to every component.

Parsy

# <Component Name>

* Author: `<Name> <Email>`
* Date: `<Date, formatted 15-03-2017>`
* Repository name: `The name of the repository that you propose.`

## Goals

Show other developers what you are planning to build and how you wish to accomplish it.

## References

Link to relevant materials, such as UX spec, related articles, etc.

## Requirements

- Talk about behaviors that the component must have.
- Talk about any performance constraints.
- Talk about how the component should interact with other components.
- Talk about how the component should behave on different screen sizes.

# Case studies `<Optional>`

Talk about one or more applications that use this (or a very similar) component. 
Case studies would usually include something novel or noteworthy that will inform 
the design. For example, you may reference App X which has a view that would use 
10,000 instances of this component and thus have extremely high performance needs.
Don't go overboard with different cases.

## Existing implementations

Talk about versions of this component that exist in other libraries, looking at 
capabilities, public API, implementation approach, accessibility, and performance.
Screenshots and/or API examples are very helpful. 

For each thing looked at, analyze:
- **What does this do well?**
- **What could this do better?**

## Proof of concept

If you created a proof-of-concept demo, link it here. Use [CodePen][codepen].

## API

Talk primarily about the public API of the components (both in templates and in 
component code). The following is an example API format that you can re-use.

## Constraints

It is invalid to create an `<span>` with for example the classes `block spread`.
Component

## Classes

Name | Type | Description
------|------|-------------
left | "position" | Will align the component to the left.
open | "state" | Whether the example is opened or closed.

## Accessibility `<Important>`

You should talk about all accessibility concerns here. See [this article] for a 
good overview of accessibility concerns.
If the component is one listed in the [WAI-ARIA Authoring Practices doc], be sure 
to address the practices and guidance given there.

### How to use the component with a keyboard only

This includes having keyboard shortcuts for all of the actions and managing focus.

### How a screen-reader user will interact with the component

This includes providing semantic meaning, text alternatives, labelling, and 
announcements (using ARIA). The overall user-experience with a
screen-reader should be well understood.

### How the component will work without color

Are there any colors being used that would not be discernable by colorblind users?
> Note: there are some Chrome extensions that attempt to simulate what a color-blind
> user would see: [SEE], [Daltonize]

### How the component will enforce any a11y requirements

Some components may require the user to provide messages, labels, or additional 
keyboard shortcuts. These requirements should be strongly enforced in dev mode.

## Roadmap and timeline

Talk about how the work can be split up into different milestones and the timing for
completion.

[this article]: https://www.polymer-project.org/0.5/articles/accessible-web-components.html
[Daltonize]: https://chrome.google.com/webstore/detail/chrome-daltonize/efeladnkafmoofnbagdbfaieabmejfcf
[SEE]: https://chrome.google.com/webstore/detail/see/dkihcccbkkakkbpikjmpnbamkgbjfdcn
[WAI-ARIA Authoring Practices doc]: https://www.polymer-project.org/0.5/articles/accessible-web-components.html
[codepen]: https://codepen.io
