
# Day 2

## DOM

In this section, we will start writing the DOM tree of an HTML document or file. DOM stands for Document Object Model. The DOM is structure like a true. It starts with an _html_ root element followed by head and body. The head and the body are the immediate children of the root element, _html_. Before the root element, there is a declaration.

### Declaration

Before the root element, there is a declaration. This declaration tells the browser that the document is an HTML. Therefore, the browser render it to the way an HTML suppose to be rendered.

This is the code to declare an HTML. The declaration is not part of the DOM tree.

```html
<!DOCTYPE html>
```

### Root Element

The _html_ element is the root of the DOM tree and is the parent of _head_ and _body_.

The DOM try has to be wrapped by the html tag.

```html
<!DOCTYPE html>
<html></html>
```

The _html_ tag with two children, head and body.

```html
<!DOCTYPE html>
<html>
  <head></head>
  <body>
    content goes here
  </body>
</html>
```

Create folder on the desktop and give it any name and even you may call it (10DaysOfHTML), inside this folder create an index.html file. Every HTML file has to end with a .html extension. And it is good to have at least on index.html file in the a project and the reset of the file will have different names.

This a simplistic DOM structure that contains _html_, _head_, _title_, _body_, _h1_ elements.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <h1 id="first-title">The Building Blocks of the web</h1>
  </body>
</html>
```

The DOM tree of the above HTML looks like the following diagram.


### Heading Elements

HTML is a markup language. We mark a content using an HTML tag and the browser render it to a clean web page. The h1 tag means making a text to be a large font size text, by default it creates 32px size text. We have h1 to h6 different tags to write different font size title. Pixel(px) is a unit to measure size which is as small as a dot.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <h1>First level heading</h1>
    <h2>Second level heading</h2>
    <h3>Third level heading</h3>
    <h1>Fourth level heading</h1>
    <h4>Fifth level heading</h4>
    <h6>Sixth level heading</h6>
  </body>
</html>
```

The size of the h1 to h6 tags:

- h1 is 32px (2em)
- h2 is 24px (1.5em)
- h3 is 20.8px (1.3em)                                 
- h4 is 16px (1em)
- h5 is 12.8px (0.8em)
- h6 is 11.2px (0.7em)

### Paragraph Element

Now, let's add paragraph to our web page using the _p_ tag.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <h1 id="first-title">The Building Blocks of the web</h1>
    <p>
      There is not website without HTML. Learn HTML and build websites and web
      applications
    </p>
  </body>
</html>
```

Now, there are six elements in the above HTML code. An HTML element may have a parent, a child, sibling(s). The _html_ element is the root or the parent of the _head_ and _body_. The _head_ and _body_ are children of the _html_ tag.The _head_ and _body_ are siblings. The _title_ is the child of the _head_. The body has two children, the h1 and p.

### Section Element

If we went to create section for our page, we can use div or section element. Section element has semantic meaning.
Let's add div in the previous page.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <div>
      <h1 id="first-title">The Building Blocks of the web</h1>
      <p>
        There is not website without HTML. Learn HTML and build websites and web
        applications
      </p>
    </div>
  </body>
</html>
```

As you can see from the above code, all the elements inside the body are wrapped by a div.
Instead of div, a section can be also used

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <section>
      <h1 id="first-title">The Building Blocks of the web</h1>
      <p>
        There is not website without HTML. Learn HTML and build websites and web
        applications
      </p>
    </section>
  </body>
</html>
```

### Header Section

Now, let us add header to our web page using the _header_ HTML tag.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <header>HTML</header>
    <section>
      <h1 id="first-title">The Building Blocks of the web</h1>
      <p>
        There is not website without HTML. Learn HTML and build websites and web
        applications
      </p>
    </section>
  </body>
</html>
```

In side the header, we can add any kind of HTML element. But I like to style the four letters of the HTML text. Therefore, I have to tag them in _span_ element.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <header>
      <span>H</span>
      <span>T</span>
      <span>M</span>
      <span>L</span>
    </header>
    <section>
      <h1 id="first-title">The Building Blocks of the web</h1>
      <p>
        There is not website without HTML. Learn HTML and build websites and web
        applications
      </p>
    </section>
  </body>
</html>
```

### Main Section

Let's make use of the _main_ HTML tag to wrap all the content that will go to the main section.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <header>
      <span>H</span>
      <span>T</span>
      <span>M</span>
      <span>L</span>
    </header>
    <main>
      <section>
        <h1 id="first-title">The Building Blocks of the web</h1>
        <p>
          There is not website without HTML. Learn HTML and build websites and
          web applications
        </p>
      </section>
    </main>
  </body>
</html>
```

### Footer Section

There is a _footer_ HTML tag to make a footer. Let us create footer for the web page.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>
      10 Days Of HTML</title>
  </head>
  <body>
    <header>
      <span>H</span>
      <span>T</span>
      <span>M</span>
      <span>L</span>
    </header>
    <main>
      <section>
        <h1 id="first-title">The Building Blocks of the web</h1>
        <p>
          There is not website without HTML. Learn HTML and build websites and
          web applications
        </p>
      </section>
    </main>
    <footer>Copyright 2022 | Priyanshu Mundra</footer>
  </body>
</html>
```

Instead of just throwing text in the footer tag let us add a _small_ HTML tag to wrap the text and it will be render to a small size text.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <header>
      <span>H</span>
      <span>T</span>
      <span>M</span>
      <span>L</span>
    </header>
    <main>
      <section>
        <h1 id="first-title">The Building Blocks of the web</h1>
        <p>
          There is not website without HTML. Learn HTML and build websites and
          web applications
        </p>
      </section>
    </main>
    <footer>
      <small>Copyright 2022 | Priyanshu Mundra</small>
    </footer>
  </body>
</html>
```

### Inline Style

We can apply CSS to an HTML element using inline styling.


We use the _style_ attribute to apply CSS to an HTML element.
For instance, let us apply style to h1.

```html
<h1 id="first-title" style="color:green">The Building Blocks of the web</h1>
```

We can add more CSS properties by separating with semicolons

```html
<h1 id="first-title" style="color:green;font-size:90px; background:blue;">
  The Building Blocks of the web
</h1>
```

As you can see from above code, _font-size_ and _background_ properties have been used.

Similarly let us apply style to the _span_ elements.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <header>
      <span style="color: #e34c26">H</span>
      <span style="color: #264de4">T</span>
      <span style="color: #f0db4f">M</span>
      <span style="color: #61dbfb">L</span>
    </header>
    <main>
      <section>
        <h1 id="first-title">The Building Blocks of the web</h1>
        <p>
          There is not website without HTML. Learn HTML and build websites and
          web applications
        </p>
      </section>
    </main>
    <footer>
      <small>Copyright 2022 | Priyanshu mundra</small>
    </footer>
  </body>
</html>
```

Colors can be described by name, hexadecimal, RGB(Red, Green, Blue), and HSL(Hue, Saturation, Lightness).

There about 1.67 million colors and it hard to describe them by name. There are about 140 colors that can be described by name and the rest of the colors can be described using hexadecimal, RGB, or HSL. One form of the color can be converted the other.
Let see the different form of the color red(name), hexadecimal(#ff0000), RGB(rgb(255, 0, 0)) and HSL(hsl(0, 100%, 50%))






## Exercise

1. What is the acronym DOM stands for?
2. What is the root of the DOM tree?
3. What are the children of _html_ tag
4. How many children can the head have?
5. How many children can the body have?  
   Make a DOM tree of the following HTML code

```html
<!DOCTYPE html>
<html>
  <head>
    <title>10 Days Of HTML</title>
  </head>
  <body>
    <header>
      <span style="color: #e34c26">H</span>
      <span style="color: #264de4">T</span>
      <span style="color: #f0db4f">M</span>
      <span style="color: #61dbfb">L</span>
    </header>
    <main>
      <section>
        <h1 id="first-title">The Building Blocks of the web</h1>
        <p>
          There is not website without HTML. Learn HTML and build websites and
          web applications
        </p>
      </section>
    </main>
    <footer>
      <small>Copyright 2022 | priyanshu mundra</small>
    </footer>
  </body>
</html>
```
