# Website for Gruppo Nairobi

Can be viewed at [https://overmeyers.github.io/grupponairobi/](https://overmeyers.github.io/grupponairobi/).

## Site Setup

The site is currently setup as a simple html and css site, with a page for the italian translation and a page for 404 errors. All the site resources are in the assets folder, including the stylesheet.

## Responsiveness & Accessibility

The site is responsive by default, without media queries. It will simply adjust and shrink or grow to the viewport, from mobile to desktop. The markup and colours are also a11y friendly which means that the site should be easily navigated with a screen reader as proper semantic elements were used, and the colour contrast meets the minimum 4.5:1 ratio. 

## Style Modifications

The stylesheet was organized into layers to create separations. The base `@layer` contains a `:root` element where variables hold things like the font families, colours and layout and sizing variables. Changes should be made in this `:root` element within the base layer rather than within the style declarations. If colour changes are to be made, keep in mind the aformentioned contrast requirements for accessibility.
