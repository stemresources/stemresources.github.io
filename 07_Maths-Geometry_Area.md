---
title: Geometry - Area Introduction
parent: 07 Maths
grand_parent: Lesson Plans
nav_order: 1
---

# Area

*Resources:* 

[Shady Shapes Handout](/assets/07Maths/geometry-01-shady_shapes.pdf) | [Area of a Rectangle Booklet](/assets/07Maths/geometry-01-area_rectangle_booklet.pdf) | 

Mini-whiteboards | [pHet - Area Builder 1.1.20](https://phet.colorado.edu/en/simulation/area-builder)

---



## Do Now: Shady Shapes

How many 1x1 squares are in each figure?

**Extension**:
Count ALL of the squares in each of the figures (eg. 1x1 squares AND 2x2 squares, 3x3 squares, etc.)

---

## Mini whiteboards

Did anyone find a fast way to add up the number of squares?

*Hint: We can use our timestables...*

-------

### Learning Intention

Students will be able to Find the formula for the area of a rectangle. (VCMMG258).

### Success Criteria

🌒 Level 1 - I can correctly solve 5 picture-based problems using the formula for the area of a rectangle. (Activity 1)
🌓 Level 2 - I can correctly solve 5 word-based problems using the formula for the area of a rectangle. (Activity 2)
🌕 Level 3 - I can correctly solve 5 compound area problems using the formula for the area of a rectangle.

-----

## Why do we need to know about area?

---

## Some skills that require area

- Estimating amount of paint to cover a wall
- Carpet laying
- Roofing
- Turfing
- Mulching a garden

Any other examples can you think of?

---

## Vocabulary

- *Dimension:* a measurement of a particular kind, such as width, or height.

- *Right-angle:*  an angle of 90°, as in a corner of a square.
- *Perpendicular:* At an angle of 90° to.
- *Perimeter:* the boundary of a closed geometrical figure. (1D)
- *Area:* the size of a surface. (2D)

---

## What is a rectangle





----

## Area of a Rectangle

$$
Area_{rectangle} = width \times height
$$



STEP 1 – Write down formula
STEP 2 – Substitute values and calculate area.
STEP 3 – Show your units.



---

End.

---

Compiling lesson using Marp in the Command Prompt:

```shell
cd C:\Users\Lochlan\Documents\GitHub\stemresources.github.io

SET markdownfile=[filename].md

# Convert slide deck into HTML
# npx @marp-team/marp-cli ECHO %markdownfile%
# npx @marp-team/marp-cli %markdownfile% -o output.html

# Convert slide deck into PDF
npx @marp-team/marp-cli %markdownfile% --pdf
npx @marp-team/marp-cli %markdownfile% -o output.pdf

# Convert slide deck into PowerPoint document (PPTX)
npx @marp-team/marp-cli %markdownfile% --pptx
npx @marp-team/marp-cli %markdownfile% -o output.pptx

# Watch mode
npx @marp-team/marp-cli -w %markdownfile%

# Server mode (Pass directory to serve)
npx @marp-team/marp-cli -s ./slides
```

[filename]: 07_Maths-Geometry_Area