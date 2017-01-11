# md-books

## CSS Naming Conventions

This project loosely follows [SUIT CSS naming conventions](https://github.com/suitcss/suit/blob/master/doc/naming-conventions.md) and is broken up by component.

We also use `-modifier` classes to create variants of a class. For example, buttons have different sizes represented by:
- `Button -sm`
- `Button -md`
- `Button -lg`

## CSS Structure

### `css/main.css`
The main file used to import all other CSS.

### `css/normalize.css`
Makes browsers render all elements more consistently.

### `css/base.css`
Contains styles for foundational elements. No specific classes should go here.

### `css/utils.css`
Contains globally applicable utility classes that can be applied to any element to modify its style.

### `css/elements/Element.css`
Elements are the simplest reusable building blocks of the site.

### `css/components/Component.css`
Components are more complex, yet still reusable sections of the site, and may use elements or other components in them.
