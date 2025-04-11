<!DOCTYPE html>
<html lang="fr">
  <head>
    <title>Titre de la page</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="" type=""/>
    <link rel="stylesheet" href=".css">
  </head>
  <body>
  </body>
</html>

/_ 1. Use a more-intuitive box-sizing model _/
_, _::before, \*::after {
box-sizing: border-box;
}

/_ 2. Remove default margin _/

- {
  margin: 0;
  }

body {
/_ 3. Add accessible line-height _/
line-height: 1.5;
/_ 4. Improve text rendering _/
-webkit-font-smoothing: antialiased;
}

/_ 5. Improve media defaults _/
img, picture, video, canvas, svg {
display: block;
max-width: 100%;
}

/_ 6. Inherit fonts for form controls _/
input, button, textarea, select {
font: inherit;
}

/_ 7. Avoid text overflows _/
p, h1, h2, h3, h4, h5, h6 {
overflow-wrap: break-word;
}

/_ 8. Improve line wrapping _/
p {
text-wrap: pretty;
}
h1, h2, h3, h4, h5, h6 {
text-wrap: balance;
}

/_ 9. Create a root stacking context
_/
#root, #\_\_next {
isolation: isolate;
}
