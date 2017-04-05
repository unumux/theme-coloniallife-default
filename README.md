# Colonial Life Theme

For use with [Willow Components](https://github.com/unumux/willow), this theme will brand your project according to [Colonial Life Brand Standards](http://toolkit.coloniallifeux.com/).

All Includes preset theme variables and icon files.

## Variables

Variables are great for 2 things:

1. Creating new components that use the existing variables so they inherit the same brand standards as other **Willow Components**

1. They can be overwritten if you need to adjust the existing theme or create one of your own

### Creating New Components

If creating a new component, you do the following to utilize the theme:

- First write the component HTML and make sure it meets [accessibility](https://unumux.github.io/enterprise-accessibility-standards) and [CSS and SCSS] (https://github.com/unumux/ux-standards/wiki/CSS-&-SCSS-Standards) standards
- Create a style folder for the component to hold its variables and styling
- Create a variables.scss file and within it create variables for the parts of the component that need to inherit from the theme
  - _Example: `$component-{component name}-background-color`, `$component-{component name}-text-color`, `$component-{component name}-border-radius`_
- Assign existing theme variables as the values of your new variabless - theme variables can be found `{theme name}/variables/theme ...


### Overwriting Variables
