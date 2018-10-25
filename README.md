This repository contains all of the CSS styles used throughout [my site](https://jfenn.me/). I generally use a [submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) that pulls from the `css` branch of this repository in each of my projects. This ensures that simply updating the css in this repository cannot break anything; I must update the submodule in each repository before the changes are applied.

## Conventions

At the suggestion of a friend, I have decided to adopt the [Block Element Modifier](http://getbem.com/naming/) naming convention in order to help organize my css more efficiently. In order to prevent this from becoming a cluttered mess, I am also using [SCSS](https://sass-lang.com/) (Sassy CSS) to split sets of styles into individual files for each element.

## Documentation

I am currently working on documenting all of the existing styles, as well as enforcing some kind of consistency between class names. When it is complete, the full documentation (and sample elements) will be available at [jfenn.me/styles](https://jfenn.me/styles/).
