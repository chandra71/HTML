

LEVEL-1  

 Hyper Text Markup Language
 HTML is the code that is used to
 structure a web page and its content.
 The component used to design the
 structure of websites are called HTML tags


 First HTML File
 index.html   
 It is the default name for a website's homepage

 HTML Tag  
 A container for some content or other HTML tags

 ```bash
 <p>
 This is a paragraph
 Content
 </p>
 ```


 Basic HTML Page
```bash
<!DOCTYPE html>
 <html>
 <head>
 <title>My First Page</title>
 </head>
 <body>
 <p>hello world</p>
 </body>
 </html
```
Quick Points

Html tag is parent of head & body tag  
 Most of html elements have opening & closing tags
 with content in between  
 Some tags have no content in between, eg - <br>  
 We can use inspect element/view page source to edit html


 HTML is NOT case sensitive
```bash
 <html> = <HTML>
 <p> = <P>
 <head> = <HEAD>
 <body> = <BODY>
 ```

 Level-2

 Basic HTML Tags  
 HTML Attributes  
 Attributes are used to add more information to the tag  
 
 
 Heading Tag
 Used to display headings in HTML
 h1 (most important)  
 h2  
 h3  
 h4  
 h5  
 h6(least important)  


 Paragraph Tag  
 Used to add paragraphs in HTML
```bash
 <p> This is a sample paragraph </p>
```
Anchor Tag  
 Used to add links to your page
```bash
<a href="https://google.com"> Google </a>
```
Image Tag  
 Used to add images to your page
 ```bash
 <img src="/image.png" alt="Random Image"> 
 ```

 Br Tag  
 Used to add next line(line breaks) to your page  
 <br>

 Bold, Italic & Underline Tags  
 Used to highlight text in your page
 ```bash
  <b> Bold </b> 
<i> Italic </i> 
<u> Underline </u> 
```

Big & Small Tags  
 Used to display big & small text on your page
 ```bash
 <big> Big </big> 
<small> Small </small>
```
Hr Tag   
 Used to display a horizontal ruler, used to separate Content  

 ```bash
<hr>
```

  Subscript & Superscript Tag
  ```bash
  <sub> subscript </sub> 

 <sup> superscript </sup>
 ```

 Pre Tag  
 Used to display text as it is (without ignoring spaces & next line)
 ```bash
 <pre> This
 is a sample
 text.      
</pre>
```

Level-3

Page Layout Techniques  
 using Semantic tags for layout   
using the Right Tags
```bash
 <header>
 <main>
 <footer>
 ```

 Inside Main Tag  
 Section Tag  
 For a section on your page  
 Article Tag  
 For an article on your page  
 Aside Tag  
 For content aside main content(ads
```bash
<section>
<article>
<aside>
```

 Div Tag  
 Div is a container used for other HTML elements  
 Block Element (takes full width)  


 List : Div Tags
```bash
 <address>
 <article>
 <aside>
 <blockquote>
 <canvas>
 <dd>
 <div>
 <dl>
 <fieldset>
 <figcaption>
 <figure>
 <footer>
 <form>
 <nav>
 <noscript>
 <ol>
 <p>
 <pre>
 <h1>-<h6>
 <header>
 <hr>
 <li>
 <section>
 <table>
 <tfoot>
 <ul>
 <dt>
 <main>
 <video>
 ```
 Span Tag  
 Span is also a container used for other HTML elements   
 Inline Element (takes width as per size)

 List : Span Tags

```bash
<code>
 <a>
 <abbr>
 <acronym>
 <b>
 <bdo>
 <big>
 <br>
 <button>
 <dfn>
 <em>
 <i>
 <img>
 <input>
 <kbd>
 <output>
 <q>
 <samp>
 <script>
 <select>
 <small>
 <span>
 <label>
 <map>
 <object>
 <tt>
 <strong>
 <sub>
 <sup>
 <textarea>
 <cite>
 <var>
 <time>
 ```

 Level Pro

List in HTML  
 Lists are used to represent real life list data.

 unordered
 ```bash
  <ul>
 <li> Apple </li>
 <li> Mango </li>
 </ul>
 ```
 ordered
 ```bash
  <ol>
 <li> Apple </li>
 <li> Mango </li>
 </ol>
```  
Tables in HTML  
 Tables are used to represent real life table data.
 ```bash  
 <tr>         used to display table row
 ```
 ```bash
 <td>         used to display table data
 ```
 ```bash
 <th>         used to display table header
```

Tables in HTML
```bash
 <table>
 <tr>
 <th> Name </th>
 <th> Roll No </th>
 </tr>
 <tr>
 <td> Shradha </th>
 <th> 1664 </th>
 </tr>
 </table>
 ```

 Caption in Tables
 ```bash
 <caption> Student Data </caption>
 ```
 thead & tbody in Tables
 ```bash
<thead>   to wrap table head 
<tbody>   to wrap table body
```

colspan attribute  
 colspan="n"   
used to create cells which spans over multiple column  


Form in HTML  
 Forms are used to collect data from the user  
 Eg- sign up/login/help requests/contact me  
```bash
<form>
 form content
</form>
```
Action in Form  
 Action attribute is used to define what action needs to be  
 performed when a form is submitted  
 ```bash
  <form action="/action.php" >
  ```

  Form Element : Input
  ```bash
  <input type="text" placeholder="Enter Name">
```

Label
```bash
<label for="id1"> 
<input type="radio" value="class X" name="class"  id="id1">
 </label> 

<label for="id2"> 
</label> 
<input type="radio" value="class X" name="class"  id="id2">
```


All the best  :)















