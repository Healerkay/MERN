### Cascading Style Sheets (CSS)

**Cascading Style Sheets (CSS)** is a style sheet language used for describing the presentation of a document written in HTML or XML. CSS defines how elements are displayed on a webpage, including their layout, colors, fonts, and other visual aspects. Here's an overview of what CSS is used for, along with basic syntax and properties:

#### What CSS is Used For:

1. **Styling HTML Elements**: CSS is primarily used to style HTML elements, including text, images, buttons, forms, and other elements. It allows web developers to control the appearance of these elements and create visually appealing webpages.

2. **Layout Control**: CSS enables developers to control the layout of a webpage, including the positioning and sizing of elements. It offers various layout techniques such as flexbox and grid, which allow for more flexible and responsive designs.

3. **Responsive Design**: With CSS, developers can create responsive web designs that adapt to different screen sizes and devices. Media queries and viewport units are commonly used CSS features for building responsive layouts.

4. **Accessibility**: CSS can be used to improve the accessibility of a website by defining appropriate colors, fonts, and contrast ratios. This ensures that the content is readable and usable for all users, including those with disabilities.

5. **Animations and Transitions**: CSS allows for the creation of animations and transitions to enhance the user experience. Keyframe animations, transitions, and transforms are CSS features used to add dynamic effects to elements.

#### Basic Syntax and Properties:

```css
/* CSS Comment */
selector {
    property: value;
    /* Multiple properties can be defined for a single selector */
    another-property: another-value;
}

/* Example */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

h1 {
    color: #333;
    font-size: 24px;
    text-align: center;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}

.button {
    background-color: #007bff;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
