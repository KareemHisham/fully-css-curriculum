# CSS master class curriculum

Or how to master css using available free content.

<figure>
  <img src="https://images.unsplash.com/photo-1517446915321-65e972f1b494?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80" alt="Photo by Paula May on Unsplash">
  <figcaption>Photo by <a href="https://unsplash.com/@paulamayphotography">Paula May</a> on <a href="https://unsplash.com/">Unsplash</a></figcaption>
</figure>

<br/>

Learning css is easy at first place, but it become a pain in a head when you want to master it not for lack of tutorials but for lack of path or fully curriculum to mastering it, here i am going to show you how to master css by following my comprehensive curriculum collecting it from many resources in the internet.

## What is CSS?

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language like HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript. CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file, and reduce complexity and repetition in the structural content. (Source: Wikipedia)

## How this curriculum work?

In each section you can find 📖 Contents and 📚 Resources, in contents i show to you what topics included in this section then in resources sections i list some of big and most comprehensive ( articles, videos or courcess ) resources covering this topic.
But before you start you need to learn the basics of html & css then follow the Curriculum to master css.

## HTML&CSS Basics

- [html & css is hard](https://internetingishard.com/html-and-css/) - A friendly web development tutorial for complete beginners.
- [Introduction to HTML | Scrimba](https://scrimba.com/g/ghtml)
- [Introduction to CSS | Scrimba](https://scrimba.com/g/gintrotocss)
- [HTML Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=UB1O30fR-EE) - by Traversy Media on Youtube.
- [CSS Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=yfoY53QXEnI) - by Traversy Media on Youtube.

## 📆 Curriculum

CSS can be categorised into four main category:

1. **Syntax:** includes selectors, properties, values and specificity.
2. **Visual:** includes styling content, responsive web design and animations.
3. **Layout:** includes css layout ( display & positioning ).
4. **Management:** includes css preprocessors, methodologies and frameworks.

- [CSS Selectors](#css-selectors)
- [CSS Properties](#css-properties)
- [CSS Values](#css-values)
- [CSS Specificity](#css-specificity)
- [Styling Content](#styling-content)
- [CSS Layout](#css-layout)
- [Responsive Web Design](#responsive-web-design)
- [CSS Animations and Drawing](#css-animations-and-drawing)
- [CSS Preprocessors](#css-preprocessors)
- [CSS Methodologies](#css-methodologies)
- [CSS Frameworks](#css-frameworks)

### Syntax

![CSS Syntax](imgs/selector.gif)

A CSS rule-set consists of a selector and a declaration block:

The selector points to the HTML element you want to style.
The declaration block contains one or more declarations separated by semicolons.
Each declaration includes a CSS property name and a value, separated by a colon.
A CSS declaration always ends with a semicolon, and declaration blocks are surrounded by curly braces.(Source: w3schools)

### CSS Selectors

In CSS, selectors are used to target the HTML elements on our web pages that we want to style.

#### 📖 Contents

- Simple Selectors

  - Element
  - Class
  - Id
  - Universal Selector ( _, ns|_, _|_, |\* )

- Combinators & Multiple selectors

  - Group of selector [A, B].
  - Descendant selector [A B].
  - Child selector [A > B].
  - Adjacent sibling selector [A + B].
  - General sibling selector [A ~ B].

- Attribute Selectors
- Pseudo-class Selectors
- Pseudo-element Selectors

#### 📚 Resources

- [CSS Selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Selectors)
- [Simple Selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Simple_selectors)
- [Combinators & Multiple selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Combinators_and_multiple_selectors)
- [Attribute Selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Attribute_selectors)
- [Pseudo-class and Pseudo-element Selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Pseudo-classes_and_pseudo-elements)

### CSS Properties

**Note:** You will learn more about properties when you get into proper section but you can learn some generic concept like css variables.

#### 📖 Contents

- CSS Variables

#### 📚 Resources

- [Learn CSS Variables Course | Scrimba](https://scrimba.com/g/gcssvariables)
- [CSS Custom Properties Guide | CSS Tricks](https://css-tricks.com/guides/css-custom-properties/)
- [Everything you need to know about CSS Variables | Freecodecamp](https://medium.freecodecamp.org/everything-you-need-to-know-about-css-variables-c74d922ea855)

### CSS Values

CSS values are set against CSS Properties and reside within CSS declaration block, which is a part of the CSS rule / statement.
**Note:** You will learn more about each value type when you get into proper section but you can learn some generic values like rem, colors, calc ...etc.

#### 📖 Contents

- Thers is 4 types of values in css

  - Colors.
  - Length, sizes and numbers.
  - Pre-Defined Options.
  - Functions.

- How CSS values are processed.

  - [Initial value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/initial_value)
  - [Resolved value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/resolved_value)
  - [Specified value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/specified_value)
  - [Computed value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/computed_value)
  - [Used value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/used_value)
  - [Actual value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/actual_value)

#### 📚 Resources

- [Color | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
- [A Nerd’s Guide to Color on the Web | CSS Tricks](https://css-tricks.com/nerds-guide-color-web/)
- [CSS Gradients Guides | CSS Tricks](https://css-tricks.com/guides/css-gradients/)
- [A Couple of Use Cases for Calc() | CSS Tricks](https://css-tricks.com/a-couple-of-use-cases-for-calc/)

### CSS Specificity

At some point in your work, you'll find yourself in the situation where multiple CSS rules will have selectors matching the same element. In such cases, which CSS rule "wins", and ends up being the one that is finally applied to the element? This is controlled by a mechanism called the Cascade, One of the most important concepts to master as you start to dig into more advanced concepts is specificity, Specificity is basically a measure of how specific a selector is.(Source: MDN)

#### 📖 Contents

- Specificity hierarchy

  - Inline styles
  - IDs
  - Classes, attributes and pseudo-classes
  - Elements and pseudo-elements

#### 📚 Resources

- [The “C” in CSS: The Cascade | CSS Tricks](https://css-tricks.com/the-c-in-css-the-cascade/)
- [Cascading and Inheritance](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Cascade_and_inheritance)
- [CSS Basics (Part2) — Cascades](https://www.youtube.com/watch?v=tZhmjgLQgXU) - by DevTips on Youtube.
- [CSS Basics (Part6) — Specificity](https://www.youtube.com/watch?v=fy07HYm-geM) - by DevTips on Youtube.
- [inheritance](https://developer.mozilla.org/en-US/docs/Web/CSS/inheritance)
- [Debugging CSS Code](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Debugging_CSS)

### Styling Content

Once you have the ability to target html elements, styling target html element ( the content ) of your page is the next big core conecpt to master.
Styling Content involves manipulating how elements should look like, What `font-size` , `color`, `background`, `border` ...etc.

#### 📖 Contents

- Typography
  - Use HTML Tags for text
  - font-size
  - font-family
  - font-weight
  - font-style
  - line-height
  - color
  - text-align
  - text-transform
  - text-decoration
- Lists
- Links
- Media ( Image, Video and Audio )
- Tables
- Forms
- Buttons
- CSS Box Model
  - Content ( images, text .... etc )
  - Padding ( Transparent area around the content, inside of the box )
  - Borders ( goes around the padding and content )
  - Margins ( Space around elements, outside of any defined borders. )
  - Fill Area ( area the contain border, padding and content, and filling with backround and bacground-image )
  - Box Sizing
    - content-box: Width and height only apply to the content of the element
    - border-box: Include padding and border in the element's total width and height
  - Background
    - background
    - background-color
    - background-image
      - Multiple Background Images.
      - Linear Gradients.
      - Radial Gradients.
    - background-size
    - background-position
    - background-repeat
    - background-attachment
    - background-origin
    - background-clip
    - background-blend-mode
  - clip-path

#### 📚 Resources

- [The box model | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Box_model)
- [A Complete Guide to the Table Element | CSS Tricks](https://css-tricks.com/complete-guide-table-element/)
- [Styling Links | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links)

### CSS Layout

Once you have the ability to target html elements for styling, layout is the next core concept to master.
Layout involves manipulating how elements lay out on the page, How much space do they take?, Are they side by side or on top of each other?, ...etc.

#### 📖 Contents

- Normal flow
- The display property
  - Block
  - Inline
  - Inline-Block
  - Flexbox
  - Grid
  - Table
- Floats
- Positioning
  - Default ( no property specified or Static )
  - Relative
  - Absoulte
  - Fixed
  - Sticky
  - Stacking Content ( Z-Index property )
- Multiple-column layout

#### 📚 Resources

- [Learn CSS Layout](http://learnlayout.com/)
- [Building layouts with flexbox and CSS grids](https://www.youtube.com/watch?v=2GxAElWKaAo)
- [Centering in CSS: A Complete Guide | CSS Tricks](https://css-tricks.com/centering-css-complete-guide/)

- Flexbox

  - [CSS flexbox Course](https://flexbox.io/) - by WesBos
  - [Flexbox Complete Guide | CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [The Complete Illustrated Flexbox Tutorial | Freecodecamp](https://medium.freecodecamp.org/the-complete-illustrated-flexbox-tutorial-d35c085dbf35)
  - [The Ultimate Guide to Flexbox  | Freecodecamp](https://medium.freecodecamp.org/the-ultimate-guide-to-flexbox-learning-through-examples-8c90248d4676)
  - [Understanding Flexbox: Everything you need to know | Freecodecamp](https://medium.freecodecamp.org/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af)

- Grid

  - [CSS Grid Course](https://cssgrid.io/) - by WesBos
  - [CSS Grid Complete Guide | CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
  - [CSS Grid — The Beginner’s Guide | Freecodecamp](https://medium.freecodecamp.org/css-grid-the-beginners-guide-45998e6f6b8)
  - [How to create an image gallery with CSS Grid | Freecodecamp](https://medium.freecodecamp.org/how-to-create-an-image-gallery-with-css-grid-e0f0fd666a5c)

- Floats

  - [All About Floats | CSS Tricks](https://css-tricks.com/all-about-floats/)
  - [CSS Floats Explained](https://www.youtube.com/watch?v=609adV3pTME) - by DevTips on Youtube.
  - [CSS Floats and Clears Explained](https://www.youtube.com/watch?v=xFGBNv2KeVU) - by DevTips on Youtube.

- Positioning

  - [CSS Positioning - part1](https://www.youtube.com/watch?v=kejG8G0dr5U) - by DevTips on Youtube.
  - [CSS Positioning - part2](https://www.youtube.com/watch?v=Rf6zAP4YnZA) - by DevTips on Youtube.

- Multiple-column layout

  - [When And How To Use CSS Multi-Column Layout | Smashing Magazine](https://www.smashingmagazine.com/2019/01/css-multiple-column-layout-multicol/)

### Responsive Web Design

Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices desktops, tablets, and phones. (Source: w3schools)

#### 📖 Contents

- Media Queries
- Responsive Images
- Common Responsive Patterns
  - Mostly Fluid
  - Column Drop
  - Layout Shifter
  - Off Canvas
- Which Method Should You Use for Your Responsive Layout?
  - Mobile-First
  - Desktop-First

#### 📚 Resources

- [Responsive Web Design Fundamentals](https://udacity.com/course/responsive-web-design-fundamentals--ud893)
- [Responsive Images](https://udacity.com/course/responsive-images--ud882)

### CSS Animations and Drawing

CSS Animations involves manipulating how elements should look like over the time by allowing you to specify how elements change from one style to another.

#### 📖 Contents

- CSS Animations: Transforms

  - Transform translate()
  - Transform rotate() and Transform-Origin
  - Transform scale()
  - Transform skew()
  - Transform Shorthand

- CSS Animations: Transitions

  - Transition Duration
  - Transition Property
  - Transition Timing Function
  - Transition Delay
  - Transition Shorthand

- CSS Animations: Keyframes

  - CSS Animation Keyframes
  - CSS Animation Duration
  - CSS Animation Fil Mode
  - CSS Animation Iteration Count
  - CSS Animation Delay
  - CSS Animation Direction
  - CSS Animation Timing Function
  - CSS Animation Properties
  - CSS Animation Shorthand

- CSS Shapes

  - CSS Shapes: the inset() function
  - CSS Shapes: The circle() Function
  - CSS Shapes: The ellipse() Function
  - CSS Shapes: The polygon() function
  - CSS Shapes: Shapes from the Alpha Channel
  - CSS Shapes: Shapes from the Reference Box

#### 📚 Resources

- [An Introduction to Web Animations | Freecodecamp](https://medium.freecodecamp.org/an-introduction-to-web-animations-86f45de2a871)
- [A Simple CSS Animation Tutorial | Freecodecamp](https://medium.freecodecamp.org/a-simple-css-animation-tutorial-8a35aa8e87ff)
- [CSS Animation Performance](https://www.html5rocks.com/en/tutorials/speed/high-performance-animations/)

### CSS Preprocessors

The use of CSS preprocessors has become so important especially when you start working on large project.
Learn about the most famous and common used preprocessor ( SASS ), Why i use it?, How to use it? and How to writing maintainable and scalable Sass.

#### 📖 Contents

- Common Preprocessors
  - SASS
  - LESS
  - Stylus
  - PostCSS

#### 📚 Resources

- [Learn Sass In 15 Minutes | Tutorialzine](https://tutorialzine.com/2016/01/learn-sass-in-15-minutes)
- [SASS Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iEwigam3gTjU_7IA3W2WZA) - by The Net Ninja on Youtube.
- [Sass Workflow & Dev Server From Scratch Using Gulp](https://www.youtube.com/watch?v=rmXVmfx3rNo) - by Traversy Media on Youtube.
- [Sass Guidelines](https://sass-guidelin.es/)
- [How to structure a Sass project](http://thesassway.com/beginner/how-to-structure-a-sass-project)
- [PostCSS – A Comprehensive Introduction | Smashing Magazine](https://www.smashingmagazine.com/2015/12/introduction-to-postcss/)

### CSS Methodologies

If you're not careful, it is easy to write complex, confusing, and unmaintable CSS. so there is many way to manage that.

#### 📖 Contents

- Common naming conventions
  - [BEM](http://getbem.com/)
  - [OOCSS](http://oocss.org/)
  - [SMACSS](https://smacss.com/)
  - [SUITCSS](https://suitcss.github.io/)
  - [Atomic](https://acss.io/)

#### 📚 Resources

- [BEM For Beginners: Why You Need BEM | Smashing Magazine](https://www.smashingmagazine.com/2018/06/bem-for-beginners/)

### CSS Frameworks

In this area you can pick up any framework you want, but i will list here the most famous one.

#### 📖 Contents

- Bootstrap
- Bulma
- Tailwind CSS

#### 📚 Resources

- [Bootstrap](https://getbootstrap.com/)

  - [Learn Bootstrap 4 Course | Scrimba](https://scrimba.com/g/gbootstrap4)
  - [Bootstrap 4: Everything You Need to Know | Freecodecamp](https://medium.freecodecamp.org/bootstrap-4-everything-you-need-to-know-c750991f6784)
  - [Bootstrap Framework — Best Practices](https://hackernoon.com/bootstrap-framework-best-practises-b1d81c02d6cf)

- [Bulma](https://bulma.io/)

  - [learn Bulma Course | Scrimba](https://scrimba.com/g/gbulma)
  - [Bulma Crash Course](https://www.youtube.com/watch?v=IiPQYQT2-wg&index=23&list=PLillGF-RfqbZTASqIqdvm1R5mLrQq79CU) - by Traversy Media on Youtube.

- [Tailwind CSS](https://tailwindcss.com/docs/what-is-tailwind/)
  - [Vanilla CSS vs Bootstrap vs Tailwind CSS - Which one should you choose?](https://www.youtube.com/watch?v=vmXIGdP8KN8)
  - [Introduction to Tailwind CSS](https://www.youtube.com/playlist?list=PLylMDDjFIp1Dt5hWKHPIHtdF2GFAS8Ak9)
  - [Tailwind CSS](https://www.youtube.com/playlist?list=PLEhEHUEU3x5p8cxOJ27w20LffCknp935L)

## Where to go next?

In general i found this blogs, newsletter or courses the best resources to learn css in specific and web development in general and for those who prefer paid courses i list for you the best paid courses available on the web.

- Blogs

  - [WEB | Google Developers](https://developers.google.com/web/)
  - [MDN Web Docs](https://developer.mozilla.org/en-US/)
  - [Tutorialzine](https://tutorialzine.com/)
  - [SABE](https://sabe.io/)
  - [Hacks Mozilla](https://hacks.mozilla.org/)
  - [CSS Tricks](https://css-tricks.com/)
  - [Smashing Magazine](https://www.smashingmagazine.com/)
  - [scotch.io](https://scotch.io/)
  - [The Full List of 400 Slack Communities](https://medium.com/startupsco/the-full-list-of-400-slack-communities-5545e82cf65d)

- Paid CSS Courses

  - [CSS - The Complete Guide (incl. Flexbox, Grid & Sass)](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/)
  - [Advanced CSS and Sass: Flexbox, Grid, Animations and More!](https://www.udemy.com/advanced-css-and-sass/)
