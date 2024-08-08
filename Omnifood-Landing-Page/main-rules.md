# BETTER THAT WAY

## 01 ---- TYPOGRAPHY SYSTEM

### Font sizes (px)

- 10 / 12 / 14 / 16 / 18 / 20 / 24 / 30 / 36 / 44 / 52 / 62 / 74 / 86 / 98

### Font weights:

- Default: 400
- Medium: 500 | Semi-bold: 600 | Bold: 700

### Line heights:

- Default: 1
- Big headers sm: 1.05 |m: 1.2| Paragraph default: 1.6

### LETTER SPACING

- 0.75px | -0.5px

## 02 ---- COLORS:-

- Primary color: #e67e22
- Tints: #fdf2e9
- Shades: #cf711f
- Accents:
- Greys: #555 | Darker #333 |

## 03 --- SHADOWS:-

- box-shadow: 0 0 30 rgba(0, 0, 0, 0.2);
-
-

## 04 --- BORDER-RADIUS:-

- Default 9px
- Medium 11px
-

## 06 --- WHITESPACE:-

### SPACING SYSTEM (px)

- 2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128

## GLOBAL RULES IN CSS

\*{
padding: 0;
margin: 0;
box-sizing: border-box;
}

html {
font-size: 62.5%; // Percentage of user's browser font-size setting this equal to 10px
}

body {
font-family: sans-serif;
line-height: 1;
font-weight: 400;
color: #555;
}

a {
text-decoration: none;
}

li {
list-style: none
}

a, button, span {
display: inline-block
}

## Comon use cases

### links use in the same order

a:link,
a:visited {
}

a:hover,
a:active {
}

### TRICK TO MAKE BORDER INSIDE

button {
box-shadow: inset 0 0 0 3px #e67e22;
}

## YOUR OWN FRAMEWORK

NOTE dont use container class on hero section its better to be more larger than other sections usually 130rem

.container {  
 max-width: 120rem;
padding: 0 3.2rem;
margin: 0 auto;
}

.grid {
display: grid;
gap: 9.6rem;
}

.grid--2--cols {
grid-template-columns: repeat(2, 1fr);
}
.grid--3--cols {
grid-template-columns: repeat(3, 1fr);
}
.grid--4--cols {
grid-template-columns: repeat(4, 1fr);
}
