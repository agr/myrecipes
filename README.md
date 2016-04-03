# My recipes repository

## Problem statement
There are plenty ways to store recipes:
* The old school way: having a little notebook;
* Storing bunch of bookmarks in your browsers to recipes web sites
* Using some application to store it
* Start a blog and put your recipes there
* something else?

There are issues with all of above:
* Notebook does not make it easy to share recipes, and it's 21 century, I don't want any notebooks
* Web sites with recipes have a tendency to close, or change link format [happened to me]
* Apps are discontinued and either not given any export options or export is pretty useless [happened to me]
* Blog seems like a nice thing, but of little use for anyone around (for them it's just another web site, with all the issues listed above)

## Solution?
Storing recipes in DVCS encourages sharing. Cloning the repository gets you full copy, not just some links. Github supports markdown
which is naturally human readable without any software, plus allows to add some structure into text, so probably some kind of schema could
be devised to allow app access. It is unclear though how to organize repositories. One repository per recipe is an overkill, but would 
allow to collect only recipes you are interested in. Having all recipes in single repository is easier to manage, but then cloning one of
the recipes from other person's repository becomes impossible. Also, other person's recipes even if cloned would be in different repos.

## Action
I'm starting to add my recipes here, and would try to devise some kind of data schema so recipes are machine readable.