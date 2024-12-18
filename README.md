<br>

# <div align="center">**CSS Clamp Function 🧠**</div>

The clamp function is a CSS function that allows you to limit the size of an element to a specified value, it can be used to create responsive designs.

You can use it with Font Size and Width/Height for blocks and images. It's the same as using the min-width and max-width properties, but with a more flexible and powerful syntax.

```css
/* Font Size */
p {
  font-size: clamp(1rem, 2vw, 1.5rem);
}
h1 {
  font-size: clamp(2rem, 0.25rem + 5vw, 7rem);
}
```

```css
/* Blocks and Images */
.box {
  --size: clamp(250px, 80vw, 500px);
  width: var(--size);
  height: var(--size);
}
```
