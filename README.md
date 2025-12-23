# Ex08 Event Registration Web Application
## Date:23.12.25

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:


```
index.html:
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image"><img class="sec-logo" src="img/sec-logo-01as-3.png" /></div>
  </body>
</html>

global.css:
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

styles.css
.image {
  width: 393px;
  height: 79px;
}

.image .sec-logo {
  position: fixed;
  top: 0;
  left: 0;
  width: 393px;
  height: 79px;
  aspect-ratio: 4.97;
  object-fit: cover;
}
stylesguide.css:
:root {
  --variable-collection-color: rgba(234, 208, 152, 1);
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-23 105628.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
