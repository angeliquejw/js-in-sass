# JS in Sass

Original Sass selling points:
- variables
  🤷🏻‍♀️ https://caniuse.com/css-variables
- vendor prefixes
  - PostCSS, Autoprefixer
- partials
  Components, modules, styled-components, etc.
- nesting
  💡 http://tabatkins.github.io/specs/css-nesting/

more complex options, but first let's get familiar with some of the tooling that makes this possible

- template literals
  - interpolation #{$variable}

- console
  - @error, @warn, @debug directives
  - error for checking functions, mixins and providing user feedback; stops compilation process
  - warn for deprecation notices, style guide corrections; no impact on compilation; include stack trace
  - debug, print value (no stack trace)

- types
  - null
  - bool
  - number
  - string
  - list (0, one, multiple values, other lists)
  - map (key, value pairs)
  - colors! https://sass-lang.com/documentation/values/colors

- functions
  - built in (round, ceil, min, max, random)
  - custom

- tests and docs
  - https://www.oddbird.net/true/docs/
  - http://sassdoc.com/

- lodash, but make it sass
  http://davidkpiano.github.io/sassdash/sassdoc/

