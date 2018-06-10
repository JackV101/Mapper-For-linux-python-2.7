# Mapper For linux python 2.7

## Requirements:

hl.colours
mapper.pyc

## Commands:

### Setup
###### This is used to create the map array
```
mapper.setup(width,height,display progress)
```
- ```width``` - int - Sets the width in characters that your map will be starting from 0
- ```height``` - int - Sets the height in characters that your map will be starting at 0
- ```display progress``` - Bool - simply displays the line number last created

### Create Areas
###### This is used to name certain sections of your map for easy referencing coordinated later
```mapper.drawSeg(x1,y1,x2,y1,name)```
- ```x1,y1``` - int - The starting coordinates for your area
- ```x2,y2``` - int - The ending coordinated for your area
- ```name``` - str - The name of your area, this can be used to reference certain parts of you map later

### Draw
###### This is used to place a character on a single point in the array

```mapper.draw(x,y,char,colour)```

- ```x,y``` - int - The coordinates of your point
- ```char``` - str - The character that will be drawn
- ```colour``` - str - The colour of the character, black is invisible in most command lines

### Fill Map

```mapper.fill(char,colour)```
- ```char``` - str - The Character that will fill the map
- ```colour``` - str - The colour of the character that will fill the map

### Rectangle
###### This is used to draw a filled in rectangle anywhere in the map

```mapper.rect(x1,y1,x2,y2,char,colour)```
- ```x1,y1``` - int - The starting coordinates of your rectangle (top left)
- ```x2,y2``` - int - The Ending coordinated of your rectangle (lower right)
- ```char``` - str - The character used to border and fill in your rectangle
- ```colour``` - str - The colour of the character used to border and fill your rectangle

### Text
###### Used to display text on the map

```mapper.text(x,y,text,colour,centered)```
- ```x,y``` - int - The coordinates of the text, left if uncentered
- ```text``` - str - The text that will be displayed
- ```colour``` - str - The colour of the text
- ```centered``` - bool - If true the text will be horizontally centered on the coordinated

## Available colours
### Colours
**All text is lower case. Add a b in front of the colour to make is bright**
```bred```

- Red
- Green
- Yellow
- Blue
- Magenta
- Cyan
- Black
- White (37)
