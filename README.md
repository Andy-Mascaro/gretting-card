Greeting Card Builder
===

Build and deploy and greeting card maker

## Resources



### Images

- [Unsplash](https://unsplash.com/)
- [Pexels](https://www.pexels.com/)
- [Pixabay](https://pixabay.com/)
- [Burst](https://burst.shopify.com/)

### Typography (Fonts)

- [Google Fonts](https://fonts.google.com/)
- [Font Squirrel](https://www.fontsquirrel.com/)

### Color Pallets

From image:
- [Canva generate from image](https://www.canva.com/colors/color-palette-generator/)
- [Generate from image](https://imagecolorpicker.com/)
- [Coolors](https://coolors.co/image-picker)

Designer/Color Palettes
- [Colour lovers](https://www.colourlovers.com/)
- [Adobe Color wheel](https://color.adobe.com/create/color-wheel)
- [Canva Color Wheel](https://www.canva.com/colors/color-wheel/)

### CSS Grid

- [CSS Tricks Complete Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Project

Take a look at the demo pages for how-to's, ideas, inspiration. Feel free to copy,
but use _as you build_. Do not copy and change values!

Build your page in the following files:

File | Purpose
---|---
`index.html` | Main page with html and semantic elements
`global.css` | css for your page
`app.js`     | JavaScript to dynamically change presentation

## Commit

As you are working and complete small steps, stop and make a commit using the 
build-in VSCode sidebar tool:

- "Stage" the files you want to commit
- Enter a commit message and hit `CMD + ENTER` or `CTRL + ENTER` (mac or windows)

To "push" to GitHub, either hit "Sync" after committing, or hit the recycle wheel button in the lower left corner.

## Assignment

Your job is to create a greeting card build. You should have:
- At least one input
- At least one select
- Set a theme using a class
- Update an image, either using a theme or an `<img>` tag

Remember to work in small chunks! 

One approach to break down the problem:

## 1. Design a static greeting card

Make one example of your greeting card. This will help you to figure out what the needed elements and styling are.

## 2. Begin making each part dynamic

1. Choose one aspect of your greeting card
1. Create a form control for setting that aspect
1. Make sure both the source form control and the target elements have ids
1. In `app.js`, get each element by id
1. Add the right event listener for that type of form control
1. Inside the event listener, write the code to copy the value from the source form control to the target element

## 3. STRETCH: Export Image

Look at the demo for how to download the greeting card as an image:
1. Add the `<script>` tag for domtoimage
1. Add a click event listener to the export button
1. Look at the code in the demo project, but pass in the element that has your greeting card.
