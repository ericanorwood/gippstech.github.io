# Catalog Playground

Catalog pages are written in ordinary [Markdown]. You can use special code blocks (called [specimens]) to show color palettes, hints, typefaces, or even interactive [React] components. Below are a few examples of specimens you can play around with. In the [documentation][docs] you can find a list of all supported specimens and how to make use of their full potential.

## Color Swatches
Simple, individual color swatches defined with a name and hex

```color
span: 2
name: "Light Blue"
value: "#b0f6ff"
```

```color
span: 2
name: "Dark Blue"
value: "#2666a4"
```

```color
span: 2
name: "Bright Red"
value: "#ff5555"
```

## Color Palettes
Color palettes are ideal to define gradient steps or color schemes.

```color-palette
colors:
   - {value: "#c7eae5"}
   - {value: "#80cdc1"}
   - {value: "#35978f"}
   - {value: "#01665e"}
   - {value: "#003c30"}
```

## Typography
The type specimen is best used to present the ratio and hierarchy of typographical elements like headings.

```type
{
  "headings": [98,28,21,16,14,12],
  "font": "montserrat",
  "color": "#333",
  "weight": "700",
  "tracking": "0.2px"
}
```

## HTML
The HTML specimen allows the documentation of HTML as well as JavaScript and CSS based views.

```html
<textarea placeholder='Add your comment' rows='6' cols='50'></textarea>
<button style='display:block'>Submit</button>
```
