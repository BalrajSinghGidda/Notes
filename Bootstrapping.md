Bootstrap is a powerful, feature-packed frontend for website formation.

- create a new file named "index.html"
	- include the `<meta name="viewport">`
	- include `<link>` tag in `<head>` tag and `<script>` tag for js in `<body>` tag before closing it.
- `<cdn>` links
- ==**Viewport meta-**== Bootstrap is mobile first developed, in which we optimize the code for mobile devices and then scale up as necessary using css.
- ==**Box-sizing-**== For more accurate sizing.

## bootstrap components

- **==Base classes:==** bootstrap components that are largely built with the base modifier nomenclature. we group as many shared properties as possible into base class like `.btn`, then group individual styles for each variant into modifier classes like `.btn-primary` or `.btn-success`.
- ==**Modifier:**== 

> why bootstrap doesn't include an icon set by default?
> We do have our own icon set library, known as bootstrap icon library. it is a growing library of SVG icons that are designed by the Bootstrap team.

Bootstrap has a very few icon needs by default, including
- Live-icons, like glyphicons

### Changing the icon font location:

Bootstrap assumes icon font files will be located in the `../fonts/` directory, relative to the compiled CSS files. Moving or renaming those font files means updating the CSS in one of three ways:

- Change the `@icon-font-path` and/or `@icon-font-name` variables in the source Less files.
- Utilize the [relative URLs option](http://lesscss.org/usage/#command-line-usage-relative-urls) provided by the Less compiler.
- Change the `url()` paths in the compiled CSS.

Use whatever option best suits your specific development setup.