# CSS Crash Course

## 1. Introduction to CSS

CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation of a document written in HTML or XML. CSS controls the layout, colors, fonts, and overall visual styling of a web page. It allows developers to separate the content of a document from its visual presentation, making it easier to maintain and update.

## 2. CSS Selectors

CSS selectors are patterns used to select and style HTML elements. Some common types of selectors include:

### 2.1 Basic Selectors

- **Element Selector**: Selects all elements of a given type.
- **Class Selector**: Selects all elements with a specific class attribute.
- **ID Selector**: Selects an element with a specific id attribute.

### 2.2 Advanced Selectors

- **Group Selector**: Selects multiple elements and applies the same style.
- **Descendant Selector**: Selects an element that is a descendant of another element.
- **Child Selector**: Selects elements that are direct children of a specified element.
- **Attribute Selector**: Selects elements based on an attribute or attribute value.

## 3. Pseudo-Classes

Pseudo-classes are used to define the special state of an element. They are typically used to style an element when a user interacts with it.

### 3.1 Common Pseudo-Classes

- **:hover**: Applies a style when the user hovers over an element.
- **:active**: Applies a style when the user clicks on an element.
- **:focus**: Applies a style when an element gains focus (e.g., when a user clicks on an input field).
- **:nth-child()**: Selects the nth child of a parent element.

### 3.2 Structural Pseudo-Classes

- **:first-child**: Selects the first child of a parent element.
- **:last-child**: Selects the last child of a parent element.
- **:nth-of-type()**: Selects the nth child of a particular type within a parent element.

## 4. Pseudo-Elements

Pseudo-elements allow you to style specific parts of an element, such as the first letter or line of a paragraph.

### 4.1 Common Pseudo-Elements

- **::before**: Inserts content before the content of an element. Often used for decorative purposes.
- **::after**: Inserts content after the content of an element. Often used for adding small icons or styling details.
- **::first-letter**: Applies styles to the first letter of an element.
- **::first-line**: Applies styles to the first line of an element.

### 4.2 Using `::before` and `::after`

The `::before` and `::after` pseudo-elements are commonly used in combination with the `content` property to insert content before or after an element’s actual content.

## 3. Background

The `background` property in CSS is used to set the background style of an element. It can include background color, image, position, and more.

### 3.1 Background Color

- **Background Color**: Sets the background color of an element.

### 3.2 Background Image

- **Background Image**: Sets an image as the background of an element.
- **Background Position**: Positions the background image.
- **Background Repeat**: Controls if/how the background image repeats.
- **Background Size**: Defines the size of the background image.

## 4. Fonts and Text

### 4.1 Font

- **Font Family**: Sets the font of the text.
- **Font Size**: Sets the size of the font.
- **Font Weight**: Controls the boldness of the text.
- **Font Style**: Sets the style of the text (normal, italic, etc.).

### 4.2 Text Properties

- **Color**: Sets the color of the text.
- **Text Alignment**: Aligns the text within its container.
- **Text Decoration**: Adds decoration like underline, overline, or line-through.
- **Text Transform**: Controls the capitalization of the text.

## 5. Box Model

The CSS box model is a fundamental concept that includes the element's content, padding, border, and margin. Understanding the box model is key to mastering CSS layouts.

### 5.1 Box Sizing

- **Box Sizing**: Determines how the total width and height of an element is calculated.

### 5.2 Padding

- **Padding**: Controls the space between the content and the border of an element.

### 5.3 Margin

- **Margin**: Controls the space outside the border of an element.

### 5.4 Border

- **Border**: Adds a border around an element.

### 5.5 Outline

- **Outline**: Draws a line outside the border of an element. Unlike borders, outlines do not take up space.

## 6. Positioning

CSS positioning allows you to control the layout of elements relative to other elements or the browser window.

### 6.1 Static Positioning

- **Static**: The default positioning. Elements are positioned according to the normal document flow.

### 6.2 Relative Positioning

- **Relative**: Positions the element relative to its normal position.

### 6.3 Absolute Positioning

- **Absolute**: Positions the element relative to its nearest positioned ancestor, or the viewport if none exists.

### 6.4 Fixed Positioning

- **Fixed**: Positions the element relative to the browser window, staying fixed during scrolling.

### 6.5 Sticky Positioning

- **Sticky**: A hybrid of relative and fixed positioning. The element is treated as relative until it reaches a specific scroll position, then it becomes fixed.

## 7. Units in CSS

CSS uses various units for specifying lengths, sizes, and other properties.

### 7.1 Absolute Units

- **Pixels (px)**: A fixed unit equal to one device pixel.

### 7.2 Relative Units

- **Em**: Relative to the font size of the element.
- **Rem**: Relative to the font size of the root element.
- **Percentage (%)**: Relative to the parent element.
- **Viewport Width (vw)**: A unit equal to 1% of the width of the viewport (the visible area of the webpage).
- **Viewport Height (vh)**: A unit equal to 1% of the height of the viewport.

## 8. Transforms

The `transform` property in CSS allows you to apply various transformations to an element, such as rotating, scaling, skewing, or translating.

### 8.1 Common Transformations

- **Translate**: Moves the element along the X and/or Y axis.
- **Scale**: Resizes the element along the X and/or Y axis.
- **Rotate**: Rotates the element around a fixed point.
- **Skew**: Skews the element along the X and/or Y axis.

### 8.2 Combining Transforms

Multiple transforms can be applied in a single `transform` property by chaining them together, e.g., `transform: rotate(45deg) scale(1.5);`.

## 9. Transitions

The `transition` property in CSS allows you to change property values smoothly (over a given duration) rather than having them change abruptly.

### 9.1 Basic Transition

- **Transition Property**: Specifies the CSS property you want to add an effect to.
- **Transition Duration**: Specifies how long the transition effect takes to complete.
- **Transition Timing Function**: Specifies the speed curve of the transition effect (e.g., `ease`, `linear`, `ease-in`, `ease-out`).
- **Transition Delay**: Specifies a delay before the transition effect starts.

### 9.2 Applying Transitions

You can apply a transition to an element by specifying the property and duration, e.g., `transition: background-color 0.3s ease;`.

## 10. Animations

CSS animations allow you to animate transitions between different states of an element. You can create animations by defining keyframes and applying them to an element.

### 10.1 Keyframes

- **Keyframes**: Define the styles that the element will have at certain times during the animation, e.g., `@keyframes example { from {opacity: 0;} to {opacity: 1;} }`.

### 10.2 Animation Properties

- **Animation Name**: Specifies the name of the keyframe animation.
- **Animation Duration**: Specifies how long the animation should take to complete one cycle.
- **Animation Timing Function**: Specifies the speed curve of the animation (e.g., `ease`, `linear`).
- **Animation Delay**: Specifies a delay before the animation starts.
- **Animation Iteration Count**: Specifies the number of times the animation should be played.
- **Animation Direction**: Specifies whether the animation should play in reverse on alternate cycles.

### 10.3 Applying Animations

You can apply an animation to an element by specifying the keyframes and other properties, e.g., `animation: example 2s ease-in-out infinite;`.

## 11. Media Queries

Media queries allow you to apply different styles depending on the device's characteristics, such as screen width, height, orientation, and resolution.

- **Basic Media Query**: Targets devices with a screen width of 600px or less.
- **Orientation Media Query**: Targets devices in landscape orientation.
- **Resolution Media Query**: Targets devices with a specific resolution.
