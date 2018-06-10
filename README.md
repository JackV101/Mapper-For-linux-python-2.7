# Mapper-For-linux-python-2.7

## Commands:

### Setup

mapper.setup(width,height,display progress)

width - int - sets the width in characters that your map will be starting from 0
height - int - sets the height in characters that your map will be starting at 0
display progress - bool - simply displays the line number last created

### Create Areas

mapper.drawSeg(x1,y1,x2,y1,name)

x1,y1 - int - the starting coordinates for your area
x2,y2 - int - the ending coordinated for your area
name - str - the name of your area, this can be used to reference certain parts of you map later

