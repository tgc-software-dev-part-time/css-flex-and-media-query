# Lesson

## Lesson Overview

The focus of this lesson is on responsive web design. It is important for learners to understand the what, why and how of responsive web design. Responsive web design enable a webpage to adapt to multiple screen sizes such as laptop, tablet and mobile. Since most consumers are on the mobile today, it is responsive web design is crucial for every business. We won't be covering all best practices in this lesson but learners should be briefed over the list and know where to source for the information when needed.

---

## Part 1 - Display Flex

Refer to [index.html](./src/lesson/part1/index.html) and [styles.css](./src/lesson/part1/styles.css) copied from the previous lesson. In this part, we will attempt to achieve the result state in the [homework section from last lesson](https://github.com/trent-f2f-bootcamp-pt/html-and-css/blob/main/homework.md).

**Step 1: Wrap the elements within `<body>` with another `<div>` in the `index.html` file**

```html
<body>
    <div> <!-- Add this line and the closing tag -->
        <h1>My Profile</h1>
        ...
```

**Step 2: Add CSS to the `<body>` element in the `styles.css` file**

```css
body{
    display:flex;
    justify-content:center;
}
```

Run live server on the `index.html` file and you should see the expected result.

---

## Part 2 - What is Responsive Web Design & Best Practices

> Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones)
> Excerpt from [Reference Link](https://www.w3schools.com/html/html_responsive.asp)

Responsive Web Design is almost mandatory for every consumer based businesses since consumers are mostly on the mobile these days. In this part, we will apply the following to the same profile page from part 1. 

1. viewport
1. font size
1. responsive image

---

## Part 3 - Use of `@media`

{{Input concepts, replicable steps & Code Samples}}

END