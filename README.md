# Rotation Leiden

This is a project inspired by then works of UK artist Kenneth Martin, especially the work ["Rotation 'Frankfurt'"](https://www.tate.org.uk/art/artworks/martin-rotation-frankfurt-key-drawing-p05475).

Analyzing the image, we have a set of coordinates distributed according to the following drawing

![Kenneth Martin - Rotation Frankfurt](kenneth-martin-rotation-frankfurt.png)

Coordinate mapping:

```
// From function, from top left to bottom right:
const initial coordinates = [0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,14];

// mapping order variants
const mapping0 = [1,0,8,9,2,15,7,10,14,3,11,6,13,12,4,5];
const mapping1 = [12,13,1,0,3,14,2,15,11,6,10,7,4,5,9,8];
const mapping2 = [11,6,14,3,4,5,13,12,8,9,1,0,7,10,2,15];
const mapping3 = [10,7,11,6,9,8,4,5,1,0,12,13,2,15,3,14];
```


```
const lineDefinitions = [
    [3,7],
    [7,11],
    [11,15],
    [15,12],
    [12,8],
    [8,4],
    [4,0],
    [0,2],
    [2,6],
    [6,10],
    [10,14],
    [14,13],
    [13,9],
    [9,5],
    [5,1]
];

// R = red
// O = orange
// W = white
// G = green
// B = blue
const colors =  ['R','O','W','G','B','R','O','W','G','B','R','O','W','G','B'];

```


Vincent Bruijn <vebruijn@gmail.com> (c) 2025
