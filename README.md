# **Fractal Tree**

## **Description**

I created a Fractal Tree animation using Python's Turtle graphics module. The program draws a tree made of many branching lines that split into smaller branches. This type of pattern is called a fractal because the same structure repeats at smaller and smaller sizes. The colors gradually change to give the tree a glowing effect against a dark background.

## **Features**

- Draws a recursive fractal tree using Turtle graphics.
- Branches split repeatedly to create a natural tree-like structure.
- Uses color gradients that change along the branches.
- Demonstrates recursion and geometric pattern generation.
- Smooth drawing animation on a dark background for better visual effect.

## **How It Works**

- I used Python’s turtle module to draw the tree and the colorsys module to create smooth color changes.
- The program defines a function called draw_tree() that draws a branch and then calls itself to draw smaller branches.
- Each time the function runs, the branch length becomes smaller, which creates the fractal effect.
- The turtle moves forward to draw the branch, then rotates left and right to create two new branches.
- When the branch length becomes very small, the recursion stops so the program does not run forever.
- The background is set to black so the colored branches stand out clearly.


## **Future Improvements**

- Add leaves at the ends of the smallest branches.
