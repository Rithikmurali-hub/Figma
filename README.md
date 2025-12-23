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
    <div class="rithik-m">
      <img
        class="fondo-plano"
        src="img/fondo-plano-deportivo-de-baloncesto-fondo-movimiento-plano-posterior-plano-imagen-de-fondo-para-descarga-gratuita-pngtreee-1.png"
      />
      <img class="sec-logo" src="img/sec-logo-01as-3.png" />
      <img class="saveetha-removebg" src="img/saveetha-removebg-preview-2.png" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="text-wrapper">Login</div>
      <img class="vector" src="img/vector.svg" />
      <div class="text-wrapper-2">Register</div>
      <div class="text-wrapper-3">SPORTS DAY EVENTS</div>
    </div>
  </body>
</html>
style.css:
.rithik-m {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.rithik-m .fondo-plano {
  position: absolute;
  top: 79px;
  left: 0;
  width: 393px;
  height: 773px;
  aspect-ratio: 2;
  object-fit: cover;
}

.rithik-m .sec-logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 79px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.rithik-m .saveetha-removebg {
  position: absolute;
  top: 113px;
  left: 53px;
  width: 296px;
  height: 295px;
  aspect-ratio: 1;
  object-fit: cover;
}

.rithik-m .rectangle {
  position: absolute;
  top: 595px;
  left: 71px;
  width: 250px;
  height: 57px;
  background-color: #163069;
}

.rithik-m .div {
  position: absolute;
  top: 595px;
  left: 74px;
  width: 250px;
  height: 57px;
  background-color: #163069;
}

.rithik-m .text-wrapper {
  position: absolute;
  top: 603px;
  left: 73px;
  width: 248px;
  font-family: "Newsreader-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: -0.72px;
  line-height: 43.2px;
}

.rithik-m .vector {
  position: absolute;
  top: 676px;
  left: 71px;
  width: 250px;
  height: 57px;
}

.rithik-m .text-wrapper-2 {
  position: absolute;
  top: 688px;
  left: 46px;
  width: 294px;
  font-family: "Newsreader-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: -0.72px;
  line-height: 43.2px;
  white-space: nowrap;
}

.rithik-m .text-wrapper-3 {
  position: absolute;
  top: 453px;
  left: -5px;
  width: 419px;
  font-family: "Nico Moji-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  text-align: center;
  letter-spacing: -0.72px;
  line-height: 43.2px;
}

globals.css:
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

styleguide.css:

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


```

## OUTPUT:
![alt text](<Screenshot 2025-12-23 105628.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
