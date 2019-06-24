# CSS

CSS allows to create rules to control the way individual box and its content is presented.

Example styles:
Box
- width and height
- Borders (color, width, style)
- position in the browser window

Text:
Typeface, Size, Color, Italics, bold, uppercase, lowercase, small-caps

CSS rule: 
-selector and declaration

```
p {
  font-family: Arial;
}
```

Several properties specified: 

```
h1, h2, h3 {
  font-family: arial;
  color: yellow;
}
```

### External CSS

`<link href='style.css' type='text/css' rel='stylesheet'/>`

### Color

The color poperty allows to specify the coloer of thext inside any element. 
Three ways to do that: 
-RGB values
-HEX code
-Color names


### Background color

CSS treats each HTML element as it appears in the box. The background-color property sets the color of the background for that box.

Every color on computer screens is created by mixing different amount of red, green and blue.

Different way of coding color:
- RGB values (3 numbers between 0 and 255) - RGB (102, 205 170)
- Hex codes - values for red, green blue in hexadecimal code (##66cdaa)
- color names
- HSL [Hue - expressed in degrees (0-360), saturation (%), lightness -(%)]
```
body {
  background-color - #c8c8c8;
  background-color - hsl (0,0%,78%);
}
```
- Alpha - transparency (numbers from 0 to 1.0)

Other color properties:
- hue
- saturation (amount of grey in the color)
- brightness (how much black in the color)
- contrast - makes it more or less legible
- opacity (przezroczystość) - the value a number between (0.0 and 1.0)
