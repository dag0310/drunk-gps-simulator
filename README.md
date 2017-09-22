# Drunk GPS Simulator
Simulate a drunk person tracked by GPS all around the world.

**[Link to "Drunk GPS Simulator"](https://dag0310.github.io/drunk-gps-simulator/)**

## What
By clicking on the action button a list of GPS lat/lon coordinates will be generated which make up a randomly generated path. However, it is not completely random, as the angle between two lines (aka drunkeness) determines how straight or queer the path might get.

## How
I built this web app without any dependencies in a single [index.html](index.html) file using vanilla JS/CSS/HTML and a Base 64 encoded favicon image. It was quite easy to do, yet a lot of fun to develop. I tried to use as many pure functions as possible to decrease the amount of state I have to maintain. I also tried to make the code as readable as possible (although there is definitely room for improvement).

## Testing the path in "real-life"
[Using this Map Tool](https://www.darrinward.com/lat-long/) (not made by me) you can copy-paste the lat/lon data there and see it in action. Of course it only really makes sense in the desert, as the algorithm does not care about such things as houses, rivers, military bases, open manhole covers, etc.

## // TODO:
see `TODO:` comments in [index.html](index.html)