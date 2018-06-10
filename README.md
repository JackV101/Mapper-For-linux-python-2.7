# Mapper For linux python 2.7

## Requirements:

hl.colours or included modified hl.colours file

## Commands:

### Setup
###### This is used to create the map array
```
mapper.setup(width,height,display progress)
```
```width``` - int - Sets the width in characters that your map will be starting from 0
```height``` - int - Sets the height in characters that your map will be starting at 0
```display progress``` - Bool - simply displays the line number last created

### Create Areas
###### This is used to name certain sections of your map for easy referencing coordinated later
```mapper.drawSeg(x1,y1,x2,y1,name)```
```x1,y1``` - int - The starting coordinates for your area
```x2,y2``` - int - The ending coordinated for your area
```name``` - str - The name of your area, this can be used to reference certain parts of you map later

### Draw
###### This is used to place a character on a single point in the array

```mapper.draw(x,y,char,colour)```

```x,y``` - int - The coordinates of your point
```char``` - str - The character that will be drawn
```colour``` - str - The colour of the character, black is invisible in most command lines

### fill

```mapper.fill(char.colour)```
