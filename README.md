# Scsswind SCSS

Scsswind is a javascript free port of [tailwindcss](https://tailwindcss.com/), written entirely in [Sass](https://sass-lang.com/).

## Example

```
  header {
    @include use(
      bg-sky-500,
      color-white,
      h-16, 
      w-full, 
      flex, 
      justify-between, 
      items-center, 
      px-4, 
      box-border
    );
  }
```