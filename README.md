# Parsy

Parsy is an abbreviation of `Polder Knowledge Pattern Library`. Combined with the 
latin word for component `pars`. This repository contains the definitions of the 
components and patterns that we have approved to the Parsy library.

## Component and patterns you say?

We make a difference between components and patterns. In Parsy terms a component is a solution to a visual problem.
Examples of components are buttons, form controls, tables, tab controls, etc. This solution we have documented. We 
believe that components are very small. When one combines components to solve UI/UX problems, we call that a pattern.
Patterns are always a composite of smaller components.

A component doesn't need to have a style. In some situations it might be useful to have default colors
and font sizes but it is up to the end-user to decide if that should be changed or not. Inspired by 
[empties][empties-bourbon] by bourbon.

A component can have one or multiple implementations. We believe that a pattern should solve a problem without forcing
you to use a certain framework. Therefor a component starts with a good description of the goal of the component. If 
this solves your problem you can either use an existing implementation or create your own. In some eco-systems it is not 
easy to adopt a new framework or library. With Parsy we want to give you a choice!
 
## Why?

We are sure that we are solving the same UX/UI problems every day. Sometimes these problems relate to basic patterns 
and other times they are more complex. Therefor we believe in a library like this, to describe these problems so we 
are able to recognize them and choose for an existing implementation before writing our own.

These are some good reads that inspired us to start with this project:
- http://www.webdesignerdepot.com/2016/12/why-you-should-be-using-pattern-libraries/
- https://articles.uie.com/components_vs_patterns/

## Contribute

All contributions are welcome, you don't have to be a full blown front-end developer to contribute to Parsy. Not 
everybody writing a component or pattern should be able to implement it. In many cases you will recognize patterns 
by spotting repetition in user interfaces, solutions to common problems. That's exactly what we are looking for! 
Describe the problem, describe how it is solved, and create a proposal with our [template]. It doesn't have to be a 
final version. We are here to help! Every proposal will be reviewed and shaped until it is ready for approval. We 
believe that first time right doesn't exist, or it is just a lucky shot. Even if you are not sure if the problem you 
described is a pattern, please submit your idea in order to help others writing even better proposals.

### Create a new proposal

To create a new proposal fork this repository and create a new markdown file based on the [template] in this 
repository. You can create a Pull Request with the new file in the proposed directory. The file **MUST** be named with the name 
of your component or pattern.

After your PR is accepted the proposed pattern will be moved to the accepted directory by one of the owners.

### Assets

In many cases you may want to provide screenshots within your proposal. Please commit them in a subfolder per pattern 
in the [assets] directory of this repository when possible in `png` format. And link them in [Reference-style]. With 
all references at the end of your pattern markdown.

When you provide working examples, please use [CodePen] to store your example.

[template]: ./template.md
[assets]: ./assets
[Reference-style]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images
[empties-bourbon]: http://empties.bourbon.io/
[CodePen]: https://codepen.io/
