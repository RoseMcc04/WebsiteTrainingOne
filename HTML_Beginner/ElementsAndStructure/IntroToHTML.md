# Introduction to HTML

- Often the first language learned by developers, marketers, and designers; core to front-end web development
- HTML: HyperText Markup Language
    - A markup language is a computer language that defines the structure and presentation of raw text
    - In HTML, the computer can interpret raw text that is wrapped in HTML elements
    - HyperText is text displayed on a computer or device that provides access to other texts using links, also known as hyperlinks

## HTML Anatomy

- HTML element: a unit of content in a HTML document formed by HTML tags and the text or media it contains

- element
```html
<p>Hello World!</p>
```
- `<p>`: opening tag
- `Hello World!`: content
- `</p>`: closing tag

## The Body

```html
<body>
    <p>
        What's up, doc?
    </p>
</body>
```

## HTML Structure

- Organized as a collection of family tree relationships
- More complex example below:
```html
<body>
    <div>
        <h1>Sibling to p, but also grandchild of body</h1>
        <p>Sibling to h1, but also grandchild to body</p>
    </div>
</body>
```

## Headings

Hierarchy of headings: 
- `<h1>`
- `<h2>`
- `<h3>`
- `<h4>`
- `<h5>`
- `<h6>`
- Example:
```html
<h1>BREAKING NEWS</h1>
```

## Divs

- short for division or a container that divides the page into sections; useful for grouping HTML elements together
```html
<body>
  <div>
    <h1>Why use divs?</h1>
    <p>Great for grouping elements!</p>
  </div>
</body>
```

## Attributes

- look at name and value of attribute
```html
<div id="intro">
    <h1>Introduction</h1>
</div>
```

## Displaying Test
- `<p>`: contains a block of plain text
- `<span>`: contains short pieces of text or other HTML; separates small pieces of content that are on the same line as other content
- `<span>` is primarily used when you want to target a specific piece of content that is inline, or on the same line as other text

## Styling Text

- `<em>`: italicizes text
- `<strong>`: bolds text
```html
<p><strong>The Nile River</strong> is the <em>longest</em> river in the world, measuring over 6,850 kilometers long (approximately 4,260 miles).</p>
```

## Line Breaks

- `<br>`: causes a line break; only needs a starting tag

## Unordered Lists

```html
<ul>
    <li>Limes</li>
    <li>Tortillas</li>
    <li>Chicken</li>
</ul>
```

## Ordered Lists

```html
<ol>
  <li>Preheat the oven to 350 degrees.</li>
  <li>Mix whole wheat flour, baking soda, and salt.</li>
  <li>Cream the butter, sugar in separate bowl.</li>
  <li>Add eggs and vanilla extract to bowl.</li>
</ol>
```

## Images

```html
<img src="image-location.jpg" />
```
- `src` can also be a link or image address

## Image Alts

```html
<img src="#" alt="A field of yellow sunflowers" />
```

## Videos

```html
<video src="myVideo.mp4" width="320" height="240" controls>Video not supported</video>
```
