<div align="center">

# ui-components-with-blur-experiment

Using a blur effect for the visual design of UI components.

</div>

<br><br>

## Code

Using the **[CSS backdrop-filter property](https://developer.mozilla.org/de/docs/Web/CSS/backdrop-filter)**, we can add a blur effect behind
semi-transparent areas, such as panels or buttons.

For example:

```css
.my-class {
  backdrop-filter: blur(5px);
}
```

> Please be aware of the **[limited browser support](https://caniuse.com/#feat=css-backdrop-filter)**. It is possible to do a compatibility
> check with fallback styling (aka "progressive enhancement") by using the
> **[`@supports()`](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports)** CSS rule!

<br>

## Preview

This example includes both light and dark buttons as an example:

![Preview GIF](/docs/preview.gif?raw=true)
