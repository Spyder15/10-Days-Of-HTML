# Day6

## HTML Document metadata

The HTML document starts with a declaration followed by the root _<html>_ tag. Inside the _<html>_ tag, there is _<head>_ and _<body>_. The _<head>_ contains the HTML document _metadata_. Metadata contains information about the page that includes styles, scripts, and data to help software user and render the page. In this section, we will learn how to use the different metadata. Look at the table blow understand the different metadata.



Source, [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

- base: The base tag refers to the base URL for all relative URLs in a document

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- character encoding for the HTML document -->
    <meta charset="UTF-8" />

    <!-- the following meta tags for Search engine optimization(SEO)-->
    <meta name="description" content="10 Days of HTML Challenge" />
    <meta name="keywords" content="HTML, CSS, Web Development" />
    <meta name="author" content="priyanshu mundra" />
    <!-- base url https://www.30daysofreact.com -->
    <base href=" https://www.30daysofreact.com" target="_blank" />
    <!-- Goes to the task bar on the browser-->
    <title>30 Days Of HTML</title>
    <!-- to lik external css -->

    <link rel="stylesheet" href="" />
    <!-- inline styling is very tideous, we can also use internal style
     we can use tag name, id or class to select an element. Id is unique and class is for a single or group of elements

     When we select by id we use # followed by the id name and if we select by class name we use . followed by a class name.
     
     -->
    <style>
      .letter {
        font-size: 68px;
      }
      #letter-h {
        color: #e34c26;
      }
      #letter-t {
        color: #264de4;
      }
      #letter-m {
        color: #f0db4f;
      }
      #letter-l {
        color: #61dbfb;
      }
    </style>
    <!-- The script tag allows to write JS code -->
    <script>
      console.log('Welcome to 10 Days of JavaScript')
    </script>
  </head>
  <body>
    <header>
      <span class="letter" id="letter-h">H</span>
      <span class="letter" id="letter-t">T</span>
      <span class="letter" id="letter-m">M</span>
      <span class="letter" id="letter-l">L</span>
    </header>
    <main>
      <section>
        <h1 id="first-title">The Building Blocks of the web</h1>
        <p>
          There is not website without HTML. Learn HTML and build websites and
          web applications
        </p>
        <a href="https://github.com/Spyder15/10-Days-Of-HTML">10 Days Of HTML</a>
      </section>
    </main>
    <footer>
      <small>Copyright 2022 | Priyanshu Mundra</small>
    </footer>
  </body>
</html>
```

Congratulations! Now, you knew about metadata.

## Exercises

1. What are metadata elements?
2. What is id?
3. What is the difference between id and class?
4. What the is the difference between style and script?
5. What is SEO?
6. Which meta tags help to improve SEO?
7. What is internal style?
8. What tag do you use to write external style?
9. What is the difference between internal style and external style?
10. What HTML tag do you use to write a JavaScript code?
