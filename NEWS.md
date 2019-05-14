# ggsoccer 0.1.4

* Link penalty box arc to pitch specification
  * Fixes a previous issue in which the edge of a circle could be seen poking
    out from behind the pitch (#8).


# ggsoccer 0.1.3

* Generate pitch markings from a generic specification
  * This makes ggsoccer compatible with any data provider

# ggsoccer 0.1.2

* Show pitch with `scale_*_reverse`
  * Centre-circle and penalty box arcs still do not properly render when 
    `scale_*_reverse` is used
  * It appears this is an issue with ggplot2 ([#3120](https://github.com/tidyverse/ggplot2/issues/3120))

# ggsoccer 0.1.1

* Display the whole pitch by default

# ggsoccer 0.1.0

* Basic pitch map functions
* Added a `NEWS.md` file to track changes to the package.
