# Initial setup guide

Before starting to work on the project, go through these steps to make sure your project skeleton is setup correctly for your needs. Doing this later on might come with additional refactoring work.

## Blocks

Remove the boilerplate blocks at `blocks/` and only add the ones you actually need.

## Styles

### Base scale

The boilerplate sets up your project to use 10px as the base rem scale instead of 16px set by default, to reduce the necessary algebra when defining rem values. You should use rem instead of px or pt in nearly all occasions to ensure compatibility with low vision assistance tools!

If you want the default scale of 16px per rem, remove these two lines:

```CSS
/* set base scale from 16px to 10px for easy rem scaling */
html { font-size: 62.5% }
```

### Colors

Follow the instructions at TODO to add the color palette of your website. Additional colors may be added during the development process but most of your base colors should already be defined beforehand.

### Fonts

Follow the instructions at TODO to add the font-families, -styles and -sizes of your website. Additional values may be added during the development process but body and heading fonts should already be defined beforehand.