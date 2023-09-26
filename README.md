# Personal Portfolio

## Technology Used 

HTML, 
CSS, 
Responsive Design Techniques (CSS Media Queries)

## Description 

[Visit the Deployed Site](https://abenedetti27.github.io/Portfolio/)

When clicking on the links in the naviation, the page scrolls to the corresponding section. When clicking on the link to 'Projects', the page scrolls to a section that displays  images of recent projects. When presented with the first project, the image is larger and clicks-through to the deployed site. 

When hovering over the navigation, the menu buttons change color to the color of the text. This makes for a unique and pleasant experience.

When the page is resized or viewed on various screens and devices, the layout is responsive and adapts to the viewport, ensuring a seamless user experience across all devices. 

## Responsive CSS Example

Below are examples of CSS media queries and navigation element to make the page responsive:

```css
@media screen and (max-width: 992px) {
    section {
      width: 90%;
    }
}
@media screen and (max-width: 768px) {
        section {
          width: 95%;
        }
    }
@media screen and (max-width: 500px) {
        section {
          width: 99%;
        }
}
```
```css
  
nav a {
    float: left;
    color: #9bf4d3;
    text-align: center;
    padding: 14px 16px;
    text-decoration:none;
    font-size: 17px;
    display: flex;
}

nav a:hover {
    background-color: #9bf4d3;
    color: black;
}
```

## License

MIT License

Copyright (c) [2023] [Anna Rose Benedetti]

