<!-- section start -->
<!-- attr: { class:'slide-title', showInPresentation:true, hasScriptWrapper:true } -->
# HTML 5
## The past, the present, the future

<div class="signature">
    <p class="signature-course">HTML Basics</p>
    <p class="signature-initiative">Telerik Software Academy</p>
    <a href="https://telerikacademy.com" class="signature-link">https://telerikacademy.com</a>
</div>

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic00.png" style="top:55%; left:90%; width:12%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic01.png" style="top:55%; left:65%; width:17.69%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic03.png" style="top:15%; left:5%; width:18.93%; z-index:-1; transform: rotate(-5deg)" /> -->




<!-- section start -->
<!-- attr: { showInPresentation:true, hasScriptWrapper:true} -->
# Table of Contents
- [Hypertext Markup Language](#/html)
- [HTML Terminology](#/terminology)
- [HTML Document Structure](#/structure)
- [HTML Common Elements](#/commonelements)
- [Section Elements](#/sectionelements)
- [Semantic Structural Tags](#/semantic)

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic04.png" style="top:40.55%; left:70%; width:28.21%; z-index:-1; border-radius: 15px; border: 3px solid yellowgreen" /> -->




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # Hypertext Markup Language -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic05.png" style="top:45%; left:35%; width:30%; z-index:-1; border-radius: 20px" /> -->


<!-- attr: { id:'html', showInPresentation:true, hasScriptWrapper:true} -->
# <a id="html"></a>Hypertext Markup Language
- **HTML** – **H**yper **T**ext **M**arkup **L**anguage
  - A **notation for describing**
    - document structure (semantic markup)
    - formatting (presentation markup)
  - Looks (looked?) like:
    - A Microsoft Word document
- The markup tags **provide information** about the page content structure
- A **HTML** document **consists of many tags**


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 0.8em' } -->
# Creating HTML Pages
- An **HTML** document must have an **.htm** or **.html** file extension
- **HTML** files can be created with text editors:
  - _Notepad_
  - _Notepad++_
  - _Sublime Text 2/3_
  - _Atom_
  - _Visual Studio Code_
- Or **HTML** editors ([WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG) Editors):
  - Microsoft WebMatrix
  - Microsoft Expression Web
  - Microsoft Visual Studio
  - Adobe Dreamweaver


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 0.8em' } -->
# HTML – Past, Present, Future
- 1991 – HTML first mentioned – Tim Berners-Lee – HTML tags
- 1993 – HTML (first public version, published at IETF)
- 1993 – HTML 2 draft
- 1995 – HTML 2 – W3C
- 1995 – HTML 3 draft
- 1997 – HTML 3.2 – “Wilbur”
- 1997 – HTML 4 – ”Cougar” – CSS
- 1999 – HTML 4.01 (final)
- 2000 – XHTML draft
- 2001 – XHTML  (final)
- 2008 – HTML5 / XHTML5 draft
- 2011 – feature complete HTML5
- http://en.wikipedia.org/wiki/HTML5#Plan_2014

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic06.png" style="top:23.80%; left:67.37%; width:30.85%; z-index:-1" /> -->




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # HTML Terminology
## Tags, Attributes and Elements -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic07.png" style="top:55%; left:7%; width:38%; z-index:-1; border-radius: 20px" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic08.png" style="top:55%; left:52%; width:41.5%; z-index:-1; border-radius: 20px" /> -->


<!-- attr: { id:'terminology', showInPresentation:true, hasScriptWrapper:true} -->
# <a id="terminology"></a>HTML Terminology
- Concepts in **HTML**
  - **Tags**
    - Opening tag and closing tag
    - The smallest piece in HTML
  - **Attributes**
    - Properties of the tag
    - Size, color, etc…
  - **Elements**
    - Combination of opening, closing tag and attributes


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 0.9em' } -->
# HTML Tags
- **Tags** are the **smallest piece** in HTML Document
  - Start with `<` and end with `>`
- Two kinds of **tags**
  - **Opening**
    - Mark the start of an HTML element
  - **Closing**
    - Mark the end of an HTML element
    - Starts with `</`

```html
<html>
<body>
   <h1>Hello Pesho!</h1>
</body>
</html>
```

<div class="fragment balloon" style="top:68%; left:17%;">Opening tags</div>

<div class="fragment balloon" style="top:82%; left:17%;">Closing tags</div>


<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Attributes
- Attributes are **properties of HTML Elements**
  - Used to **set** `size`, `color`, `border`, etc…
  - Put **directly in the tags**
  - Has value surrounded by **single** `' '` or **double** `" "`  quotes
    - The value is always a string

```html
<!-– makes a hyperlink to Google -->
<a href="http://google.com"> go to Google</a>

<!-– makes a horizontal line -->
<hr width="95%" size="3px"/>

<!-– adds an image in the web page -->
<img src="images/SEB-Ninja.png"/>
```

<div class="fragment balloon" style="top:72%; left:58%; width:25.56%">Some  tags don't have closing tag</div>


<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Most Common Attributes
- There are some **attributes that are common** for every HTML element
  - `id`, `class`, `name`, `style`
- Some attributes are **specific**
  - For example the attribute `src` of the `img` element
    - Shows the path to the image to be shown


<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# HTML Elements
- HTML Elements are **combination of tags and attributes**
  - Opening tag with some or none attributes and a closing tag

```html
<a href="http://google.com"> go to Google</a>
```

```html
<html>…</html>
```


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # HTML Terminology -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/02.%20HTML-Fundamentals/demos/01.HTML-concepts.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic09.png" style="top:55%; left:10%; width:34.77%; z-index:-1; border-radius: 20px; transform: rotate(-5deg)" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic10.png" style="top:55%; left:57%; width:38%; z-index:-1; border-radius: 20px; transform: rotate(5deg)" /> -->


<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # HTML Document Structure
## HTML Document, Doctype, Head, Body -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic11.png" style="top:55%; left:30%; width:40%; z-index:-1; border-radius: 20px" /> -->


<!-- attr: { id:'structure', showInPresentation:true, hasScriptWrapper:true} -->
# <a id="structure"></a>HTML Document Structure
- Some elements are **essential** to each HTML Document:
    - `html`, `head`, `body`, `doctype`
- The `html` element
  - Used to **mark the beginning** and ending of a HTML document
  - All the content of the web page is inside this tag

```html
<html>
   <!-- content goes here -->
</html>
```



<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Head Element
- The `head` tag contains markup that is not visible to the user (i.e. the person using the browser)
  - But **helps the browser** to render correctly the HTML document
- **What is in there**?
  - Styles, scripts
  - Declare encodings
  - Etc..
  - The `title` tag - the text in the tab of a browser

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic13.png" style="top:50%; left:58.01%; width:25%; z-index:-1; border-radius: 15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Body Element and Doctype
- `body` element contains **all the visible to the user markup**
  - Headings, text, hyperlinks, images, etc…
  - Textboxes, sliders, buttons…
- `Doctype` is kind of the validator of the page
  - **Tells the browser** in which version of HTML the page is written
  - HTML 5 Doctype

```html
<!DOCTYPE html>
```



<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true} -->
<!-- # HTML Document Structure -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/02.%20HTML-Fundamentals/demos/02.HTML-structure.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic14.png" style="top:55%; left:7%; width:34.38%; z-index:-1; border-radius: 20px; transform: rotate(-5deg)" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic15.png" style="top:55%; left:56%; width:36.81%; z-index:-1; border-radius: 20px; transform: rotate(5deg)" /> -->


<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # HTML Common Elements
## Used in 90% of all the sites -->

<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Text Formatting
- Text formatting tags modify the text between the opening tag and the closing tag
  - Ex. <code>&lt;b>Hello&lt;/b&gt;</code> makes "Hello" bold
  - Many of the formatting tags are deprecated
    - **Use CSS instead**

<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 38px' } -->
# Text Formatting - Tags
|          Tags        |              Meaning             |
|:---------------------|:--------------------------------:|
| `<b></b>`            | <b>bold</b>                      |
| `<i></i>`            | <i>italiazed</i>                 |
| `<u></u>`            | <u>underlined</u>                |
| `<sup></sup>`        | sample<sup>superscript</sup>     |
| `<sub></sub>`        | sample<sub>bold</sub>            |
| `<strong></strong>`  | <strong>strong</strong>          |
| `<em></em>`          | <em>emphasized</em>              |
| `<pre></pre>`        | <pre>preformatted text</pre>     |

<!-- attr: { id:'commonelements', showInPresentation:true, hasScriptWrapper:true} -->
# <a id="commonelements"></a>Some Simple Tags
- Hyperlink Tags

```html
<a href="http://www.telerik.com/"
  title="Telerik">Link to Telerik Web site</a>
```
- Image Tags

```html
<img src="logo.gif" alt="logo" />
```
- Text formatting tags

```html
This text is <em>emphasized.</em>
<br />new line<br />
This one is <strong>more emphasized.</strong>
```

# Hyperlink Tags
<!-- TODO: 
- `target` attribute
  - `_blank`
  - `_self`
-->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true} -->
# Headings and Paragraphs
- Heading Tags (`h1` – `h6`)

```html
<h1>Heading 1</h1>
<h2>Sub heading 2</h2>
<h3>Sub heading 3</h3>
```

- Paragraph Tags

```html
<p>This is my first paragraph</p>
<p>This is my second paragraph</p>
```

- Sections: `div` and `span`

```html
<div style="background: skyblue;">
   This is a div
</div>
```



<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Ordered Lists: **&#60;ol&#62;** Tag
- Create an **Ordered List** using `<ol></ol>`:

```html
<ol type="1">
  <li>Apple</li>
  <li>Orange</li>
  <li>Grapefruit</li>
</ol>
```
- Attribute values for **type** are **1**, **A**, **a**, **I**, or **i**

<!-- <img class="slide-image" showInPresentation="true" src="imgs/bullets.png" style="top:55%; left:7%; width:75%; z-index:-1" /> -->



<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Unordered Lists: **&#60;ul&#62;** Tag
- Create an **Unordered List** using `<ul></ul>`:
- Attribute values for **type** are:

<!-- <img class="slide-image" showInPresentation="true" src="imgs/bullets-ul.png" style="top:35%; left:5%; width:75%; z-index:-1" /> -->



<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Definition lists: **&#60;dl&#62;** tag
- Create **definition lists** using `<dl></dl>`
  - Pairs of text and associated definition; text is in `<dt></dt>` tag, definition in `<dd></dd>` tag

```html
<dl>
<dt>HTML</dt>
<dd>A markup language …</dd>
<dt>CSS</dt>
<dd>Language used to …</dd>
</dl>
```
  - Renders **without bullets**
  - Definition is **indented**



<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true} -->
<!-- # HTML Common Elements  -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/02.%20HTML-Fundamentals/demos/03.Common-elements.html)

<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # Section Elements
## The `<div>` and the `<span>` -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic17.png" style="top:53%; left:29.5%; width:40%; z-index:-1; border-radius: 15px" /> -->


<!-- attr: { id:'sectionelements', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 0.9em;' } -->
# <a id="sectionelements"></a>The &#60;div&#62; Tag
- `<div>` creates logical<br /> divisions within a page <br /> <br/>
  - Block element <br/> <br/>
  - Used with CSS <br/> <br/>
- _Example_:

```html
<div style="font-size:24px; color:red">DIV example</div>
<p>This one is
    <span style="color:red; font-weight:bold">only a test</span>.
</p>
```

<img class="slide-image" showInPresentation="true" src="imgs/pic18.png" style="top:20.28%; left:53.12%; width:45.91%; z-index:-1; border-radius: 15px" />


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # &#60;DIV&#62; -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/02.%20HTML-Fundamentals/demos/04.Section-elements-div.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic19.png" style="top:55%; left:15%; width:42.31%; z-index:-1; border-radius: 15px" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic21.png" style="top:55%; left:65%; width:27%; z-index:-1; border-radius: 15px" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size:0.9em' } -->
# The &#60;span&#62; Tag

<ul style="width: 60%">
<li><strong>Inline style</strong> element</li>
<li>
    Useful for <strong>modifying a specific portion</strong> of text
    <ul>
        <li><strong>Don't use it to create a separate area</strong> (paragraph) in the document</li>
    </ul>
</li>

<li>Mainly used to style parts of a text</li>

</ul>

```html
<p>This one is
    <span style="color:red; font-weight:bold">only a test</span>.
</p>
<p>This one is another
    <span style="font-size:32px; font-weight:bold">TEST</span>.
</p>
```

<img class="slide-image" showInPresentation="true" src="imgs/pic22.png" style="top:15%; left:70%; width:30%; z-index:-1; border-radius: 15px" />


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # &#60;SPAN&#62; -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/02.%20HTML-Fundamentals/demos/05.Section-elements-span.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic23.png" style="top:55%; left:63.05%; width:29.5%; z-index:-1; border-radius: 15px" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic24.png" style="top:55%; left:3.74%; width:55.59%; z-index:-1; border-radius: 15px" /> -->

<!-- section start -->
<!-- attr: { id:'semantic', class:'slide-section', showInPresentation:true, hasScriptWrapper:true } -->
# <a id="semantic"></a>Semantic Structural Tags

<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# The Structure of a Web Page
- A sample layout structure of a Web Page
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic25.png" style="top:21.16%; left:12.09%; width:83.01%; z-index:-1" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# The "HTML 4 and Before" Way
- Using **divs with IDs**
  - The **IDs are needed for styling**

```html
<html>
<head> … </head>
<body>
    <div id="header"> … </div>
    <div id="navigation"> … </div>
    <div id="sidebar"> … </div>
    <div id="content"> … </div>
    <div id="footer"> … </div>
</body>
</html>
```

<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # The HTML 4 Way -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/02.%20HTML-Fundamentals/demos/06.Semantic-structural-tags-divs.html)

<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# The HTML5 Way
- In **HTML5** there are **semantic tags** for layout
  - `<nav>`, `<header>`, `<footer>`, `<section>`


```html
<html>
<head> … </head>
<body>
    <header> … </header>
    <nav> … </nav>
    <aside> … </aside>
    <section> … </section>
    <footer> … </footer>
</body>
</html>
```
- Work only **in newer browsers**


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true } -->
<!-- # Semantic Structural Tags -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/02.%20HTML-Fundamentals/demos/07.Semantic-structural-tags.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic26.png" style="top:55%; left:30%; width:40%; z-index:-1; border-radius: 50px 0px 50px 0" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Remember
- It is important to have the **correct vision** and **attitude** towards HTML
  - **HTML is only about structure**, not appearance
  - Browsers tolerate invalid HTML code and parse errors – you should not
  - Always think about **semantics**
- The **W3C HTML Validator** is a way to validate your HTML
  - http://validator.w3.org/


<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
<!-- # HTML Fundamentals -->

<!-- <img class="slide-image" showInPresentation="true" src="https://github.com/TelerikAcademy/Common/raw/master/revealjs-theme/css/imgs/cat-questions.png" style="width:80%; top:15%; left:10%" /> -->

<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'' } -->
# Free Trainings @ Telerik Academy
- Web front-end track
    - [html.telerik.com](http://academy.telerik.com/student-courses/web-design-and-ui/about)
  - Telerik Software Academy
    - [academy.telerik.com](academy.telerik.com)
  - Telerik Academy @ Facebook
    - [facebook.com/TelerikAcademy](facebook.com/TelerikAcademy)
  - Telerik Academy Learning System
    - [telerikacademy.com](https://telerikacademy.com)
