# Day 7

## HTML Form

A form is one part of a website. Different websites handle user data using a HTML form. For instance, when we create an account or sign in to our account we fill an input field. Filling a form on a website is a common activity. Therefore, we have to know how to build a form.
To create a form, we use _form_ element and the _form_ element wrap other input fields. The input field might be text, number, date, checkbox, radio button, file ,or others types.

```html
<form>
  <label>First name:</label>
  <input type="text" />
  <input type="submit" value="Submit" />
</form>
```

You can try the output of the above code on visual studio code.

The HTML form code below can handle different kind of data. It handles almost any kind of data including file.

```html
<h1 class="section-title">Application Form</h1>
<article class="form-article">
  <form class="contact-form">
    <div class="form-group">
      <label for="firstname">First Name</label>
      <input type="text" id="firstname" placeholder="Your name" />
    </div>
    <div class="form-group">
      <label for="lastname">Last Name</label>
      <input id="lastname" type="text" placeholder="Your last name" />
    </div>
    <div class="form-group">
      <label for="email">Email</label>
      <input type="email" id="email" placeholder="Your email" />
    </div>
    <div class="form-group">
      <label for="company">company</label>
      <input id="company" type="text" placeholder="Your company name" />
    </div>
    <div class="form-group">
      <label for="age">You age: </label>
      <input type = "number" id="age" name="age' placeholder="Age" />
    </div>
    <div class="form-group">
      <label for="date">Date of Birth</label>
      <input id="date" type="datetime-local" />
    </div>
    <div class="form-group">
      <p>What are your skills</p>
      <input type="checkbox" id="html" />
      <label for="html">HTML</label>
      <br />
      <input type="checkbox" id="css" />
      <label for="css">CSS</label>
      <br />
      <input type="checkbox" id="js" />
      <label for="js">JavaScript</label>
      <br />
      <input type="checkbox" id="react" />
      <label for="js">React</label>
      <br />
      <input type="checkbox" id="redux" />
      <label for="redux">Redux</label>
    </div>
    <div class="form-group">
      <label for="color">Your favorite</label>
      <input id="color" type="color" />
    </div>

    <div class="form-group">
      <p>Gender</p>
      <input type="radio" id="female" name="gender" />
      <label for="female">Female</label>
      <br />
      <input type="radio" id="male" name="gender" />
      <label for="male">Male</label>
      <br />
      <input type="radio" id="other" name="gender" />
      <label for="other">Other</label>
    </div>

    <div class="form-group">
      <p>Select your country</p>
      <select name="country" id="country">
        <option value="">-Country-</option>
        <option value="Finland">Finland</option>
        <option value="Estonia">Estonia</option>
        <option value="Sweden">Sweden</option>
        <option value="Norway">Norway</option>
        <option value="Denmark">Denmark</option>
      </select>
    </div>
    <div class="form-group">
      <p>Select your country</p>
      <select name="course" id="course">
        <option value="">-Select Course-</option>
        <option value="html-css">Basis of HTML and CSS</option>
        <option value="js">Modern JavaScript</option>
        <option value="pyhton">Python</option>
        <option value="react">React</option>
        <option value="data-analysis">Data Analysis with Python</option>
      </select>
    </div>

    <div class="form-group">
      <label for="message">Leave your message here</label> <br />
      <textarea
        cols="120"
        rows="10"
        id="message"
        placeholder="Write your message here..."
      ></textarea>
    </div>
    <div class="form-group">
      <input type="file" id="file-input" />
      <label for="file-input"><i class="fas fa-upload"></i>Upload File</label>
    </div>
    <div>
      <input type="checkbox" id="agree" />
      <label for="agree"
        >Be sure that all the information is yours and true.</label
      >
    </div>
    <div>
      <input type="submit" value="Submit" />
    </div>
  </form>
</article>
```

Try the output the above code on visual studio.

What is matters the most is understanding how the HTML form works, this is not an exhaustive list of all the input fields. Whenever you would like to solve some problem, try to search it on the internet using a key word. Searching is also one the most important skill in software development.
