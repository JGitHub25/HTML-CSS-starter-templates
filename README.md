# HTML - CSS Starter Templates

- Save time on project setup.
- Methodical approach to start/design a new project.
- Extended from [John Smilga's Default Starter](https://github.com/john-smilga/default-starter)
- See his [Complete Video Tutorial](https://youtu.be/UDdyGNlQK5w). I created Timestamps for it.

## Normalize

For cross-browser consistency in the default styling of HTML elements.

Alternative/Fancier way of doing this:

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

- Find it [here.](https://necolas.github.io/normalize.css/)

## Customize

Check the main properties to customize marked in the comments:

```css
/*TODO: CUSTOMIZE*/
```

You can add the [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) extension to easily see them.

## Fonts

#### Select Fonts

- [fontpair](https://www.fontpair.co/)
- [pagecloud](https://www.pagecloud.com/blog/best-google-fonts-pairings)

#### Choose a type scale

- [typescale](https://type-scale.com/)

## Colors

```css
:root {
  /* primary */
  /* grey */
  --black: #222;
  --white: #fff;
  --red-light: #f8d7da;
  --red-dark: #842029;
  --green-light: #d1e7dd;
  --green-dark: #0f5132;
}
```

#### Select Primary and Get shades

- [coolors](https://coolors.co/)
- [happyhues](https://www.happyhues.co/)
- [Palette Ninja](https://palette.ninja/)
- [Eva Design System](https://colors.eva.design/). Shades and palettes.
- Get shades [shadowlord](https://noeldelgado.github.io/shadowlord/#73fdad)

- [bootstrap](https://getbootstrap.com/docs/5.0/customize/color/#color-sass-maps)
- [tailwind](https://tailwindcss.com/docs/customizing-colors#color-palette-reference)

#### Select Grey

- [tailwind](https://tailwindcss.com/docs/customizing-colors#color-palette-reference)

#### Box Shadow

- [tailwind](https://tailwindcss.com/docs/box-shadow)

#### Main color combinations

In the ESSENTIAL variables there are 2 combinations of light/dark background/text to easily use along the project:

```css
--background-color-light: var(--grey-50);
--text-color-dark: var(--grey-900);
--background-color-dark: var(--primary-800);
--text-color-light: var(--grey-100);
```

Check you combinations accessibility w/ [ACCESSIBLE COLORS.](https://accessible-colors.com/)
