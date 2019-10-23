Skeletal - the dead simple, responsive, and variable boilerplate
================================================================

Skeletal is based on the Skeleton CSS framework. It takes all the options you
are most likely to change and pulls them out into a file of CSS variables. This
way you can keep the main file static while only changing your variables when
using the basic style in different projects. It also uses the `calc` property
liberally which means that if you change one variable all the related things
should change as well. It also adds a couple more utility classes and a navbar,
so the main site now only requires ~40 lines of CSS to show the examples while
everything else is pure Skeletal. In this repository you will find the two main
files for skeletal `css/skeletal.css` and `css/variables.css`. In addition you
will find `css/normalize.css` from https://necolas.github.io/normalize.css/.
While not strictly required to use Skeletal there are some styles that won't
work properly and cross-browser consistency might suffer. As an example you
will also find the `https://skeletal.peterme.net` website source, along with
the little splash of custom css that is required for that to work.
