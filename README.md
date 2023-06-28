# Personal Profile

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |  
| Git | [https://git-scm.com/](https://git-scm.com/)     |    

## Description 
This is a personal Profile of Xiaoran Cai. The page have 3 sections: (1) monthly highlights (2) Applications (3)Life. The goal is to present Xiaoran as a whole person. 

The picture

## Code Refactor Example

```html
<div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
```

Converting the above non-semantic div with the class of 'header' to an appropriate [<header> semantic element](https://www.w3schools.com/html/html5_semantic_elements.asp). 

```html
<header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>

```

This change require some additional modification to the CSS selector: 

```css
.header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}
```

No longer targeting the element on the page with the class of 'header' but instead the css selector targeting the 'header' element 

```css
header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

```

## Usage 

![Final Product](./assets/images/01-html-css-git-homework-demo.png)

## Learning Points 

* Use semantic HTML
* The HTML elements need to follow a logical structure independent of styling and positioning
* The title of the page needs to be meaningful
* Adding "alt" helps people to understand the webpage better if pictures do not show

## Author Info

### Xiaoran Cai

* [LinkedIn](https://www.linkedin.com/in/xrcai/)
* [Github](https://github.com/Aillycxr)

## Credits
* W3school| [https://www.w3schools.com](https://www.w3schools.com)    

## License

Copyright (c) Microsoft Corporation. All rights reserved.
Licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.

## Features
The nevigation bar items link to their content repectively




