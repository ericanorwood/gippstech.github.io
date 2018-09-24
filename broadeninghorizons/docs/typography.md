The following are guidelines for the use of type throughout the website.

# Headings
The font used is [Nobile](https://fonts.google.com/specimen/Nobile?selection.family=Nobile:400,500).

```type
{
  "headings": [72,48,36,28,16,14],
  "font": "nobile",
  "color": "#333",
  "weight": 500,
  "tracking": 1,
}
```

## Specific heading styling
Any additional specific styles for headings are specified below. Please see [basestyles.css](/docs/basestyles.css) for the CSS code. Otherwise, headings default to the styling specified above.

### H2 alternates
```html|showSource,span-3
<h2 class="h2style">The quick brown fox</h2>
```

```html|showSource,span-3
<h2 class="h2style-light">jumps over the lazy dog</h2>
```

### H4 alternates
```html|showSource
<h4 class="h4style">The quick brown fox jumps over the lazy dog</h2>
```


# Body
Body text is rendered in [Open Sans](https://fonts.google.com/specimen/Open+Sans).

```type
{
  "paragraphs": ["16/24"],
  "font": "open sans",
  "color": "#333",
  "weight": 400,
}
```
