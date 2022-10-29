---
layout: post
title:  "Design Elements and Pathfinding"
author: moe
categories: [ Design ]
tags: [ Lessons, Foundations, Theory ]
image: assets/images/15.png
---
In this post, we're going to begin exploring the basic terms used when creating a composition. We will also explore how to create a grid, a point, a line, and a plane. Afterwards, we're going to explore the very basics of pathfinding and how to use it as a technique to create complex shapes.

These are the basic building blocks you'll need to begin experimenting with design.

I encourage you to recreate these as you read along to gain a deeper understanding of how to apply these elements visually.

## Artboard
An uninterrupted space enclosed within borders defines an artboard.
![Defining an artboard within an empty space](/assets/images/pathfinding/1.png "Creating an Artboard")



## Grids
One of the biggest hurdles for creatives is creating something out of nothing. Your new best friend as a designer is a grid. A grid is several uninterrupted vertical and horizontal lines of equal spacing overlayed on the artboard. Typically the grid doesn't show in the final work, but perhaps you could explore using the grid as a design element. Your grid will allow you to create to work within set rules and constraints.

![Defining a grid within an artboard measuring 5x5](/assets/images/pathfinding/2.png "Creating a Grid")



## Planes
We can create a plane by selecting a space enclosed by grid lines.

Let's fill in the space in black. Congratulations! We've just created our very first design elements, a plane.

![Creating a plane defined by a space enclosed by grid lines](/assets/images/pathfinding/3.png "Creating a Plane")

If you move the plane in a manner where it's borders are always parallel to the artboard, we create a change in **position**.

![Changing the position of a plane by moving in a manner parallel to the artboard's axis](/assets/images/pathfinding/4.png "Changing Position of a Plane")


If we tilt the plane so that it's edges are no longer parallel to the borders, we create a **rotation** and a change in the **direction** of the element.

![Changing the direction of a plane by rotating the element](/assets/images/pathfinding/5.png "Changing the Direction of a Plane")

How we choose to divide the artboard we're working on can be determined either as pre-conditions that come as a nature of the area we are working with or as a design decision.

For example; I might want to design with a specific proportional system in mind, or might have to adjust the grid to work with an unorthodox shape.



## Pathfinding
When you position elements on top of one another, we can utilise what is typically called "pathfinding".  Pathfinding can create different results, depending on which method you choose.

### Division
The two elements can differentiate themselves by creating a borderline that divides them.

![Creating a division between two elements so that they remain distinct elements](/assets/images/pathfinding/6.png "Pathfinding using Division")




### Union
The two elements can be superimposed and united into a new object. You can create complex forms by joining different elementary shapes together.

![Creating a union between two elements turning them into a new object](/assets/images/pathfinding/7.png "Pathfinding using Union")


### Subtraction
You can subtract one element from the other to create a new complex form. You can treat it like an equation where one shape is "positive" space, and the other is "negative".

![Substracting one element from another to create a new object](/assets/images/pathfinding/8.png "Pathfinding using Subtraction")


### Intersection
You can subtract the parts of two elements that do not intersect with one another.

![Intersecting to elements and subtract the parts that do not overlap to create a new object](/assets/images/pathfinding/9.png "Pathfinding using Intersection")



### Exclusion
You can also subtract the parts of two elements that do intersect with one another, and only keep the parts that do not overlap.

![Subtracting parts of the elements that overlap, and keeping the remainder to create a new object](/assets/images/pathfinding/10.png "Pathfinding using Exclusion")

## Lines

A line is a directional element with a length greater than it's width. It can divide or encircle an area.

Let's create a line out of the planar element we were working with previously. We need to get rid of the black fill and divide the area we were working with into smaller *sub-grids* or sub-divisions within the grid.

![Creating a sub-grid within a grid](/assets/images/pathfinding/11.png "Sub-grids")

When we apply a fill into one length, we create a line.

![Creating a line element](/assets/images/pathfinding/12.png "Lines")

A line can come in different forms: it can be a clean straight line or have a jagged, pointed, or a rounded tip, and it can be textured, rectilinear or curved.

The length of a line can be extended and joined to another line, or utilised with pathfinding to create a division, union, subtraction, or intersection.



### Rectilinear Lines vs Curvilinear Lines
Rectilinear lines move in parallel to a rectangular grid axis. In other words, they only ever intersect with one another at 90-degree angles.

Curvilinear lines are more fluid and can curve along different points of a grid.

![Showing a rectilinear and a curvilinear line to clearly show the difference between both line types](/assets/images/pathfinding/13.png "Curvilinear vs Rectilinear Lines")



## Points
Points don't necessarily need to have a width or length, nor do they need to have a fill. They can either be invisible elements or treated as smaller planes.

There is a big difference between points and planes. We can make the difference clearer by carefully considering how we represent a point.

If we represent a "point" like a "plane", it's size must be relatively small in comparison to the artboard's area and the other planar elements in the composition.

Typically points are presented as circles. The reason being a circle is a non-directional shape. If you use a different shape like a triangle or a square, you can begin to express a direction.

![Showing a point defined by a grid subdivisions](/assets/images/pathfinding/14.png "Point")


## Final Thoughts
We've covered the basics of form-making, and explaining the differences between a plane, a line, and a point. We've also introduced the basic idea behind pathfinding, and if you've ever used Adobe Illustrator, you might already be familiar with this concept.

Of course, the grid system will have a dedicated post in the future because there is a lot to be said about using a grid.

Now that I've introduced you to the basics of form-making, I highly encourage you to experiment with them to gain a deeper understanding of them. There's only so much I can explain in writing, but you do need to practice to gain a real appreciation of what we've covered.

I highly encourage you to experiment and explore the boundaries between what makes a dot, a line, and a plane. I also encourage you to experiment in form-making using pathfinding as a technique to generate complex geometry from basic shapes. If you're looking for an example, look at the first and last image in this composition, and try to decipher how they were created using only the principles we've discussed here.

![A composition created using Direction, Rotation, Position, and Pathfinding](/assets/images/pathfinding/15.png "Composition")

## Further Reading
[Stefan, A. (2016, January 7). Illustrator in 60 Seconds: How to Use the Pathfinder Tool. Design & Illustration Envato Tuts. https://design.tutsplus.com/tutorials/illustrator-in-60-seconds-how-to-use-the-pathfinder-tool--cms-25572](https://design.tutsplus.com/tutorials/illustrator-in-60-seconds-how-to-use-the-pathfinder-tool--cms-25572)

[Krammer, C. (2018, May 14). Sketch tip: How boolean operations work - Design + Sketch. Medium. https://medium.com/sketch-app-sources/the-way-boolean-operations-work-69c183082427](https://medium.com/sketch-app-sources/the-way-boolean-operations-work-69c183082427)

[Dave, S. (2018, March 20). Speed up Sketch workflow using Boolean Operations - UX Collective. Medium. https://uxdesign.cc/understanding-boolean-operations-in-sketch-2928eea0c7d0](https://uxdesign.cc/understanding-boolean-operations-in-sketch-2928eea0c7d0)
