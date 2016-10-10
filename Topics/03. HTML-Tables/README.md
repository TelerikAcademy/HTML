<!-- section start -->
<!-- attr: { class:'slide-title', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# HTML Tables
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic00.png" style="top:54.85%; left:45%; width:28.28%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic02.png" style="top:66.60%; left:63%; width:5.11%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic03.png" style="top:48.57%; left:75%; width:30.50%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic04.png" style="top:5.99%; left:15%; width:22.69%; z-index:-1" /> -->

<div class="signature">
    <p class="signature-course">HTML Basics</p>
    <p class="signature-initiative">Telerik Software Academy</p>
    <a href="https://telerikacademy.com" class="signature-link">https://telerikacademy.com</a>
</div>



<!-- section start -->
<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Contents
- [HTML Tables](#/tables)
  - [Simple Tables](#/simpletables)
  - [Data cells and Header cells](#/headers)
  - [Complete HTML Tables](#/completetables)
- [Nested Tables](#/nestedtables)
- [Complex tables](#/comlextables)
  - [Cell Spacing and Padding](#/cells)
  - [Column and Row Span](#/spans)

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic05.png" style="top:21.83%; left:69.10%; width:37.47%; z-index:-1; border-radius: 15px; border: 3px solid yellowgreen" /> -->




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # HTML Tables -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic06.png" style="top:7%; left:20%; width:60%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic07.png" style="top:33.16%; left:0%; width:25.08%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic08.png" style="top:56.78%; left:50%; width:37.02%; z-index:-1" /> -->


<!-- attr: { id:'tables', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="tables"></a>HTML Tables
- Tables represent tabular data
  - A table consists of one or several rows
  - Each row has one or more columns
- Tables are comprised of several core tags:
  - `<table></table>`:  begin/end table definition
  - `<tr></tr>`: create a table row
  - `<td></td>`: create tabular data (cell)
- Tables should not be used for layout
  - Use CSS floats and positioning styles instead


<!-- attr: { id:'simpletables', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="simpletables"></a>Simple HTML Tables – _Example_

```html
<table cellspacing="0" cellpadding="5">
  <tr>
    <td><img src="ppt.gif"></td>
    <td><a href="lecture1.ppt">Lecture 1</a></td>
  </tr>
  <tr>
    <td><img src="ppt.gif"></td>
    <td><a href="lecture2.ppt">Lecture 2</a></td>
  </tr>
  <tr>
    <td><img src="zip.gif"></td>
    <td>
      <a href="lecture2-demos.zip">Lecture 2 - Demos</a>
      </td>
  </tr>
</table>
```



<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Simple HTML Tables -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/03.%20HTML-Tables/demos/1.%20Simple-tables.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic09.png" style="top:0%; left:63%; width:40%; z-index:-1; border-radius: 15px" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic10.png" style="top:10%; left:20%; width:25.67%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic11.png" style="top:49.19%; left:11.04%; width:24.68%; z-index:-1; border-radius: 15px" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic12.png" style="top:50.84%; left:64.50%; width:37.02%; z-index:-1" /> -->


<!-- attr: { id:'headers', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="headers"></a>Data Cells and Header Cells
- Two kinds of cells in HTML tables
  - `Data` cells – containing the table data
  - `Header` cells – used for the column names or some more important cells
- Why two kinds of cells?
  - Used to `semantically` separate the cells

```html
<tr>
    <th>Full Name</th> <th>Mark</th>
</tr>
<tr>
    <td>Doncho Minkov</td> <td>Very good (5)</td>
</tr>
<tr>
    <td>Georgi Georgiev</td> <td>Excellent (6)</td>
</tr>
```



<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Data and Header Cells -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/03.%20HTML-Tables/demos/2.%20Data-and-header-cells.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic13.png" style="top:55%; left:60%; width:22.92%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic14.png" style="top:55%; left:17%; width:22.92%; z-index:-1" /> -->




<!-- section start -->
<!-- attr: { id:'completetables', class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="completetables"></a>Complete HTML Tables
## With Header, Footer and Body
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic15.png" style="top:60%; left:75%; width:15%; z-index:-1" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Complete HTML Tables
- Table rows split into three semantic sections: `header`, `body` and `footer`
  - `<thead>` denotes table header and contains `<th>` elements, instead of `<td>` elements
  - `<tbody>` denotes collection of table rows that contain the very data
  - `<tfoot>` denotes table footer but comes **BEFORE** the `<tbody>` tag
  - `<colgroup>` and `<col>` define columns (used to set column widths)


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Complete HTML Table: _Example_

```html
<table>
  <colgroup>
    <col style="width:100px" /><col />
  </colgroup>
  <thead>
    <tr><th>Column 1</th><th>Column 2</th></tr>
  </thead>
  <tfoot>
    <tr><td>Footer 1</td><td>Footer 2</td></tr>
  </tfoot>
  <tbody>
    <tr><td>Cell 1.1</td><td>Cell 1.2</td></tr>
    <tr><td>Cell 2.1</td><td>Cell 2.2</td></tr>
  </tbody>
</table>
```

<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Complete HTML Table: _Example_

```html
<table>
  <colgroup>
    <col style="width:200px" /><col />
  </colgroup>
  <thead>
    <tr><th>Column 1</th><th>Column 2</th></tr>
  </thead>
  <tfoot>
    <tr><td>Footer 1</td><td>Footer 2</td></tr>
  </tfoot>
  <tbody>
    <tr><td>Cell 1.1</td><td>Cell 1.2</td></tr>
    <tr><td>Cell 2.1</td><td>Cell 2.2</td></tr>
  </tbody>
</table>
```

<div class="fragment balloon" style="top:59.88%; left:33.50%; width:46.72%">Although the footer is before the data in the code, it is displayed last</div>
<!-- <img class="slide-image fragment balloon" showInPresentation="true" src="imgs/pic18.png" style="top:15%; left:36.65%; width:63.80%; z-index:1" /> -->


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Complete HTML Tables -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/03.%20HTML-Tables/demos/3.%20Complete-tables.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic19.png" style="top:55%; left:30%; width:40%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic20.png" style="top:50%; left:25%; width:18%; z-index:-1" /> -->

<!-- section start -->
<!-- attr: { id:'nestedtables', class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="nestedtables"></a>Nested Tables
## Tables in Tables in Tables in Tables…
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic21.png" style="top:53%; left:7.11%; width:35%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic22.png" style="top:53%; left:62.31%; width:30%; z-index:-1" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Nested Tables
- Table **cells** (`<td>`) can contain **nested** tables (tables within tables):

```html
<table>
  <tr>
    <td>Contact:</td>
    <td>
      <table>
        <tr>
          <td>First Name</td>
          <td>Last Name</td>
        </tr>
      </table>
    </td>
  </tr>
</table>
```

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic23.png" style="top:49.41%; left:63.27%; width:40.44%; z-index:1" /> -->


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Nested Tables -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/03.%20HTML-Tables/demos/4.%20Nested-tables.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic24.png" style="top:7.35%; left:75%; width:29%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic25.png" style="top:10.40%; left:0%; width:24%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic26.png" style="top:55%; left:20%; width:23.60%; z-index:-1" /> -->


<!-- section start -->
<!-- attr: { id:'comlextables', class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # <a id="comlextables"></a> Complex Tables
## With Padding, Spacing and Stuff -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic28.png" style="top:55%; left:30%; width:40%; z-index:-1" /> -->


<!-- attr: { id:'cells', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="cells"></a> Cell Spacing and Padding

<div>
  <div class="balloon" style="top:20%;left:15%">cell spacing</div>
  <div class="balloon" style="top:20%;left:60%">cell padding</div>
</div>

<!-- <img class="slide-image" showInPresentation="true" src="imgs/cell-spacing-padding.png" style="top:25%; left:10%; width:80%; z-index:-1" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Cell Spacing and Padding – _Example_

```html
<html>
  <head><title>Table Cells</title></head>
  <body>
    <table cellspacing="15" cellpadding="0">
      <tr>
          <td>First</td>
          <td>Second</td>
      </tr>
    </table>
    <br/>
    <table cellspacing="0" cellpadding="10">
      <tr>
          <td>First</td>
          <td>Second</td>
      </tr>
    </table>
  </body>
</html>
```



<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Cell Spacing and Padding – _Example_ -->

```html
<html>
  <head><title>Table Cells</title></head>
  <body>
    <table cellspacing="15" cellpadding="0">
      <tr>
          <td>First</td>
          <td>Second</td>
      </tr>
    </table>
    <br/>
    <table cellspacing="0" cellpadding="10">
      <tr>
          <td>First</td>
          <td>Second</td>
      </tr>
    </table>
  </body>
</html>
```

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic29.png" style="top:34.53%; left:65%; width:43.53%; z-index:1" /> -->


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Cell Spacing and Cell Padding -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/03.%20HTML-Tables/demos/5.%20Table-cells-spacing-padding.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic30.png" style="top:50%; left:73.76%; width:25.34%; z-index:-1; border: 3px solid yellowgreen" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic31.png" style="top:45%; left:7.06%; width:22.52%; z-index:-1; border: 3px solid yellowgreen" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic32.png" style="top:0%; left:40.23%; width:40%; z-index:-1; border: 3px solid yellowgreen" /> -->




<!-- section start -->
<!-- attr: { id:'spans', class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="spans"></a>Row and Column Spans
## How to Make a Two-Cells Column or Row?
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic33.png" style="top:55%; left:15.91%; width:23.03%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic34.png" style="top:5%; left:18.31%; width:18.51%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic35.png" style="top:60%; left:59.98%; width:23.03%; z-index:-1" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Column and Row Span -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/rowspan-colspan.png" style="top:20%; left:12.5%; width:75%; z-index:-1" /> -->

<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } 
# Column and Row Span – _Example_ -->

```html
<table cellspacing="0">
  <tr class="1">
  	<td>Cell[1,1]</td>
  	<td colspan="2">Cell[2,1]</td>
  </tr>
  <tr class="2">
  	<td>Cell[1,2]</td>
  	<td rowspan="2">Cell[2,2]</td>
  	<td>Cell[3,2]</td>
  </tr>
  <tr class="3">
  	<td>Cell[1,3]</td>
  	<td>Cell[2,3]</td>
  </tr>
</table>
```

<!-- <img class="slide-image fragment balloon" showInPresentation="true" src="imgs/rowspan-colspan-example.png" style="top:45%; left:55%; width:50%; z-index:1" /> -->


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Row and Column Spans -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/03.%20HTML-Tables/demos/6.%20Table-colspan-rowspan.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic36.png" style="top:45%; left:65.50%; width:25%; z-index:-1" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # HTML – Tables and Forms -->
<!-- ## Questions? -->

<!-- <img class="slide-image" showInPresentation="true" src="https://raw.githubusercontent.com/TelerikAcademy/Common/master/revealjs-theme/css/imgs/questions-blue.png" style="width:60%; top:20%; left:20%; border-radius: 50px 0 50px 0" /> -->

<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'' } -->
# Free Trainings @ Telerik Academy
- Web front-end track
    - [html.telerik.com](http://academy.telerik.com/student-courses/web-design-and-ui/about)
  - Telerik Software Academy
    - [telerikacademy.com](https://telerikacademy.com)
  - Telerik Academy @ Facebook
    - [facebook.com/TelerikAcademy](facebook.com/TelerikAcademy)
  - Telerik Academy Learning System
    - [telerikacademy.com](https://telerikacademy.com)
