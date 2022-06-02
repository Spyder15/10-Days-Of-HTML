# Day 8

## HTML Table

In this section, we will see how to create an HTML table. Table has an external border, header rows and header cell, body rows and its cells and it could have also a footer row. To make an HTML table, we need a _table_ element that wrap all the rows and the rows wrap all the data cells.

```html
<table>
  <tr>
    <td>Name</td>
    <td>Gender</td>
    <td>Country</td>
  </tr>
  <tr>
    <td>Asabeneh</td>
    <td>250</td>
    <td>Finland</td>
  </tr>
</table>
```

Let us see the output of the above code

<table>
  <tr>
    <td>Name</td>
    <td>Gender</td>
    <td>Country</td>
  </tr>
  <tr>
  <td>priyanshu</td>
  <td>250</td>
  <td>india</td>
  </tr>
</table>

However, HTML table has _thead_, \*tbody and tfooter. Let us add thead and tbody to the above code. In addition, we can use th in the table head instead to td to make the table heading bold.

```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Gender</th>
      <th>Country</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>spyder</td>
      <td>250</td>
      <td>india</td>
    </tr>
  </tbody>
</table>
```

Try the output of the above code using visual studio code.

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Gender</th>
      <th>Country</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Priyanshu
      <td>250</td>
      <td>india</tr>
  </tbody>
</table>

The author of this challenge creates different challenges every year. Let us put all his challenges on a table.

```html
<html>
  <head>
    <title>1 Days Of HTML: Table</title>
    <style>
      /* Table CSS */
      table,
      td,
      th {
        border: 2px solid gray;
        border-collapse: collapse;
        border: 1px solid #a785df;
      }
      table {
        margin-top: 15px;
        width: 75%;
      }
      td {
        padding-left: 10px;
      }
      th {
        background-color: #7433df;
        color: white;
      }
    </style>
  </head>
  <body>
    <table>
      <thead>
        <tr>
          <th>Challenge</th>
          <th>Days</th>
          <th>Time</th>
          <th>Stars(K)</th>
          <th>URL</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1 Days of Python</td>
          <td>1</td>
          <td>june 2022
          <td>4.9td>
          <td>
            <a href=" https://github.com/Spyder15?tab=repositories"ink</a>
          </td>
        </tr>
        <tr>
          <td>10Days of JavaScript</td>
          <td>10/td>
          <td>june 2022</td>
          <td>6.8K</td>
          <td>
            <a href="https://github.com/Asabeneh/30-Days-Of-JavaScript">Link</a>
          </td>
        </tr>
        <tr>
          <td>30 Days of React</td>
          <td>30</td>
          <td>October 2020</td>
          <td>5.6K</td>
          <td>
            <a href="https://github.com/Spyder15?tab=repositories">Link</a>
          </td>
        </tr>
        <tr>
          <td>10 dof HTML</td>
          <td>1</td>
          <td>may 2022 </td>
          <td>33</td>
          <td>
            <a href="https://github.com/Spyder15?tab=repositories">Link</a>
          </td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```

Try the output the above code on visual studio
