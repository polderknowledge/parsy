# Parsy

Parsy is an abbreviation of `Polder Knowledge Pattern Library`. Combined with the 
latin word for component `pars`. This repository contains the definitions of the 
patterns that we have approved.

## What is a pattern

In Parsy terms a pattern is a filed template. Just a page of documentation how a common UX/UI
problem should be solved. We believe that a basic pattern is very small. The more complex patterns
are always a composite of smaller patterns. In extreme you can state that a html element is a kind of
pattern to solve a common UI problem.

A pattern doesn't need to have a style. In some situations it might be useful to have default colors
and font sizes but it is up to the user of the pattern to decide if that should be changed or not. Inspired
by [empties][empties-bourbon] by bourbon.

A pattern can have one or multiple implementations. We believe that a pattern should solve a problem without forcing
you to use a certain framework. Therefor a pattern starts with a good description of the goal of the pattern. If this
 solves your problem you can either use an existing implementation or create your own. In some eco-systems it is not 
 easy to adopt a new framework or library. You should be able to choose!
 
## Why?

We are sure that we are solving the same UX/UI problems every day. Sometimes the basic patterns and sometimes the 
complex ones. Therefor we believe in a library like this to describe these problems so we are able to recognize them
and choose for an existing implementation before writing our own.

This are some good reads that inspired us to start with this project:
- http://www.webdesignerdepot.com/2016/12/why-you-should-be-using-pattern-libraries/
- https://articles.uie.com/components_vs_patterns/

## Contribute

All contributions are welcome, you don't have to be a full blown front-end developer to contribute to Parsy. Not 
everybody writing a pattern should be able to implement it. In many cases you will recognize patterns in a UI. 
Solutions to common problems. That's exactly what we are looking for! Describe the problem, describe how it is 
solved, and create a proposal with our [template]. It doesn't have to be a final version. We are here to help! Every 
proposal will be reviewed and shaped until it is ready for approval. We believe that first time right doesn't exist, 
or it is just a lucky shot. Even if you are not sure if the problem you described is a pattern please submit your 
idea that will help others to write even better proposals.

### Create a new proposal

To create a new proposal fork this repository and create a new markdown file based 
on the [template] in this repository. You can create a PR with the new file in the
proposed directory. The file **MUST** be named with the name of your pattern.

After your PR was accepted the proposed pattern will be moved to the accepted 
directory by one of the owners.

### Assets

In many cases you may want to provide screenshots within your proposal. Please 
commit them in a subfolder per pattern in the [assets] directory of this repository
when possible in `png` format. And link them in [Reference-style]. With all 
references at the end of your pattern markdown.

[template]: ./template.md
[assets]: ./assets
[Reference-style]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images
[empties-bourbon]: http://empties.bourbon.io/
