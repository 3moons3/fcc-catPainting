# Learn Intermediate CSS by Building a Cat Painting

Mastering CSS positioning is essential for creating visually appealing and responsive web layouts

In this course, you will build a cat painting. You'll learn about how to work with absolute positioning, the z-index property, and the transform property.

## Step 1

Begin with the basic HTML structure. Add a DOCTYPE reference of html and an html element with its lang attribute set to en. Also, add a head and a body element within the html element.

## Step 2

Within your head element, add a meta tag with the charset attribute of utf-8. Also add a title element with the text fCC Cat Painting.

## Step 3

Add a link element within your head element. For that link element, set the rel attribute to stylesheet and the href to ./styles.css.

## Step 4

Use the universal selector to add box-sizing: border-box; to your CSS. This ensures elements include padding and border in their specified width and height.

## Step 5

Give your body element a background-color of #c9d2fc.

## Step 6

Back in your HTML, create a main element. Inside that main element, add a div element with the class cat-head.

## Step 7

Using a class selector, give the .cat-head element a width of 205px and a height of 180px. Also, give it a border of 1px solid #000 and a border-radius of 46%.



* {
  box-sizing: border-box;
}

body {
  background-color: #c9d2fc;
}

.cat-head {width: 205px; height: 180px; border: 1px solid #000; border-radius: 46%;}




## Step 8

To see the .cat-head element, give it a linear gradient background with #5e5e5e at 85% and #45454f at 100%.

You might not notice the difference between these two colors, but they are there.

## Step 9

CSS positioning lets you set how you want an element to be positioned in the browser. It has a position property you can set to static, absolute, relative, sticky or fixed.

Once you set the position property of the element, you can move the element around by setting a pixel or a percentage value for one or more of the top, right, left, or bottom properties.

static is the default positioning for all elements. If you assign it to an element, you won't be able to move it around with top, right, left, or bottom.

Give .cat-head a position property of static, then set the top and left properties to 100px each.

## Step 10

You could see that nothing happens. The .cat-head element did not move despite setting a top and left of 100px each. But that's not the case with relative positioning.

When you use the relative value, the element is still positioned according to the normal flow of the document, but the top, left, bottom, and right values become active.

Instead of static, give your .cat-head a position of relative, and leave both top and left properties as they are.

## Step 11

The next position property is absolute. When you use the absolute value for your position property, the element is taken out of the normal flow of the document, and then its position is determined by the top, right, bottom, and left properties.

Set the position property of your .cat-head element to absolute, then set top and left properties to any positive pixel value.

## Step 12

fixed is a position property value that lets you make an element fixed to the page no matter where the user scrolls to on the page.

You'll have to do some more markups to see how fixed positioning works. In your HTML, create a div element with the class box.

## Step 13

Use a class selector to give your .box element a width of 200px, a height of 600px, and a background color of #000. Also, give it a position of absolute, a top of 800px and a left of 650px.

## Step 14

Now replace the position property value of your .cat-head with fixed. Leave both top and left as they are.

After that, scroll up and down to see how the fixed value works.

## Step 15

The last position property value is sticky. sticky positioning is a hybrid of relative and fixed positioning. It allows an element to stick to a specific position within its containing element or viewport, based on the scroll position.

Change the value of the position property of .cat-head to sticky, set top to 0, then remove left and its value.

Note: To see how sticky works, you have to place a couple of texts before and after your .cat-head div element. If you scroll down after that, you'll see that the .cat-head gets stuck to the top and remains there.

## Step 16

You should now center the cat head.

Give the .cat-head element a position property set to absolute. Set a value of 0 for the right, left, top, bottom properties, then set its margin property on all sides to auto. That's one way to center an element vertically and horizontally using CSS positioning.

## Step 17

Remove the div element with class box because you don't need it anymore.

## Step 18

Also, remove the .box CSS rule and its declarations because you don't need them anymore.

## Step 19

Now you should work on the cat's ears. There will be a right and a left ear, and inside each, there will be an inner ear.

Inside your .cat-head element, create a div element with the class cat-ears.

## Step 20

Inside your `.cat-ears` element, create two `div` elements with the classes `cat-left-ear` and `cat-right-ear` respectively.



