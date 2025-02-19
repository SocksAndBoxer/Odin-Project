# SVG

## Scalable Vector Graphics

A way to create images using math instead of pixels

### Advantages

- quality: make them bigger but not blurry
- Weight: since it's created with maths it's always the same since
- Readability: written in XML, which means better readability
- Integration: you can just put it directly in an HTML file

### Drawbacks

- Inefficient: complex images are a pain (eg: grunge textures)

## Anatomy of an SVG

- **xmlns**: XML NameSpace, specifies the *language* of the SVG (for the browser)
- **viewBox**: defines position, aspect ratio and origin
- **class, id**: same as HTML Element
- **`<use>`**: reuse an element inside the SVG by using its *id*
- **circle, rect, path, text**: SVG building blocks

## Embedding SVGs

You can include an SVG in an HTML file the same way you would an image:

- `<img>` Element in the HTML
- *background-image* CSS Property (eg: `background-image: url(./some-image.svg)`)
  making it inaccessible from the browser
- paste the content directly into the HTML, making it accessible, therefore editable,
  and worse code readability/loading time

## Resources

[The course](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-svg#embedding-svgs)
Free SVG libraries: [Material Icons](https://fonts.google.com/icons), [Feather icons](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-svg#embedding-svgs)
[SVG Editor in browser]
