<!-- section start -->
<!-- attr: { id:'', class:'slide-title', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# HTML Forms and Frames
<img class="slide-image" src="imgs/pic00.png" style="top:35%; left:85%; width:25%; z-index:-1" />
<img class="slide-image" src="imgs/pic01.png" style="top:55%; left:50%; width:30.50%; z-index:-1" />
<img class="slide-image" src="imgs/pic02.png" style="top:55%; left:15%; width:25%; z-index:-1" />




<!-- section start -->
<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# Table of Contents
- HTML Forms
  - Form Fields and Fieldsets
  - Text Boxes
  - Buttons
  - Checkboxes and Radio Buttons
  - Select Fields
  - Hidden Fields
  - Sliders and Spinboxes
  - Validation Fields
<img class="slide-image" src="imgs/pic03.png" style="top:20%; left:76.72%; width:24.24%; z-index:-1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# Table of Contents
- HTML Frames
  - Frame and **noframe** tags
  - **iframe** tag
<img class="slide-image" src="imgs/pic05.png" style="top:47.83%; left:21.52%; width:20.62%; z-index:-1" />
<img class="slide-image" src="imgs/pic06.png" style="top:29.74%; left:57.08%; width:41.32%; z-index:-1" />




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# HTML Forms
## Entering User Data from a Web Page
<img class="slide-image" src="imgs/pic07.png" style="top:55%; left:40.60%; width:22%; z-index:-1" />
<img class="slide-image" src="imgs/pic08.png" style="top:4.94%; left:74.38%; width:25.12%; z-index:-1" />
<img class="slide-image" src="imgs/pic09.png" style="top:29.97%; left:92.63%; width:5.29%; z-index:-1" />
<img class="slide-image" src="imgs/pic10.png" style="top:15.26%; left:8.71%; width:14.10%; z-index:-1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# What are HTML Forms?
- The **primary** method for gathering data from site visitors
- HTML Forms can contain
  - **Text** fields for the user to type
  - **Buttons** for interactions like<br /> "**Register**", "**Login**", "**Search**"
  - **Menus**, **Sliders**, etc…
- Check Google, Yahoo, Facebook
  - Google search field is a simple **Textfield**
<img class="slide-image" src="imgs/pic11.png" style="top:32.62%; left:80.00%; width:20.28%; z-index:-1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# How to Create a HTML Form?
- Create a form block with
```html
<form></form>
```
- _Example_:


```html
<form name="myForm" method="post" action="path/to/some-script.php">
   ...
</form>
```

<div class="fragment balloon" style="top:50%; left:41%; width:63.78%">The "action" attribute tells where the form data should be sent</div>
<div class="fragment balloon" style="top:30%; left:41.43%; width:58.60%">The "method" attribute tells how the form data should be sent – via GET or POST request</div>


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# Text Fields
- **Single-line** text input fields:

```html
<input type="text" name="FirstName" value="This is a text field" />
```
- **Multi-line** text input fields (**textarea**):

```html
<textarea name="Comments">
    This is a multi-line text field
</textarea>
```
- **Password** input – a text field which masks the entered text with ***** signs

```html
<input type="password" name="pass" />
```

<img class="slide-image" src="imgs/pic12.png" style="top:13%; left:69.24%; width:25%; z-index:-1" />
<img class="slide-image" src="imgs/pic13.png" style="top:30.63%; left:86.08%; width:20%; z-index:-1" />
<img class="slide-image" src="imgs/pic14.png" style="top:68%; left:78.79%; width:25%; z-index:-1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 36px' } -->
# Buttons
- **Reset** button – brings the form to its initial state
```html
<input type="reset" name="resetBtn"   
  value="Reset the form" />
```
- **Submit** button:
```html
<input type="image" src="submit.gif"
  name="submitBtn" alt="Submit" />
```
- **Image** button – acts like submit but image is displayed and click coordinates are sent
```html
<input type="button" value="click me" />
```
- **Ordinary** button – no default action, used with JS
```html
<input type="submit" value="Apply Now" />
```


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# Checkboxes and Radio Buttons
- **Checkboxes**:
```html
<input type="checkbox" name="fruit" value="apple" />
```
- **Radio** buttons:
```html
<input type="radio" name="title" value="Mr." />
```
- Radio buttons can be grouped, allowing **only one** to be selected from a group:
```html
<input type="radio" name="city" value="Lom" />
<input type="radio" name="city" value="Ruse" />
```

<img class="slide-image" src="imgs/pic15.png" style="top:14%; left:47.72%; width:15%; z-index:-1" />
<img class="slide-image" src="imgs/pic16.png" style="top:35%; left:44.91%; width:25%; z-index:-1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# Select Fields
- **Dropdown** menus:

```html
<select name="gender">
  <option value="Value 1"
    selected="selected">Male</option>
  <option value="Value 2">Female</option>
  <option value="Value 3">Other</option>
</select>
```
- **Multiple-choice** menus:

```html
<select name="products" multiple="multiple">
  <option value="Value 1"
    selected="selected">keyboard</option>
  <option value="Value 2">mouse</option>
</select>
```

<img class="slide-image" src="imgs/pic17.png" style="top:45.84%; left:95.44%; width:10.80%; z-index:1" />
<img class="slide-image" src="imgs/pic18.png" style="top:11.46%; left:79.69%; width:24.35%; z-index:1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 42px' } -->
# Hidden Fields
- **Hidden** fields contain invisible data
```html
<input type="hidden" name="Account"
  value="This is a hidden text field" />
```
  - Not shown to the user
  - Used by **JavaScript** and **server-side** code
    - **ViewState**, **SessionState** in ASP.NET


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 42px' } -->
# Labels
- **Labels** are used to associate an explanatory text to a form field using the field's ID
```html
<label for="fn">First Name</label>
<input type="text" id="fn" />
```
- Clicking on a label **focuses** its associated field
  - Checkboxes are **toggled**
  - Radio buttons are **checked**
- Labels are
  - Both a **usability** and **accessibility** feature
  - Required in to pass accessibility validation


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 42px' } -->
# Fieldsets
- **Fieldsets**are used to enclose a group of related form fields:
```html
<form method="post" action="form.aspx">
   <fieldset>
      <legend>Client Details</legend>
      <input type="text" id="Name" />
      <input type="text" id="Phone" />
   </fieldset>
   <fieldset>
      <legend>Order Details</legend>
      <input type="text" id="Quantity" />
      <textarea cols="40" rows="10" id="Remarks">
      </textarea>
   </fieldset>
</form>
```
- The **<legend>**is the fieldset's title


<!-- attr: { id:'', class:'slide-section demo', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# HTML Forms <br /> Inputs Fields
## [Live Demo]()
<img class="slide-image" src="imgs/pic19.png" style="top:11.46%; left:7%; width:21.16%; z-index:-1" />
<img class="slide-image" src="imgs/pic20.png" style="top:50.25%; left:8%; width:21.16%; z-index:-1" />
<img class="slide-image" src="imgs/pic21.png" style="top:9.99%; left:78%; width:21.16%; z-index:-1" />
<img class="slide-image" src="imgs/pic22.png" style="top:52.75%; left:80%; width:21.16%; z-index:-1" />
<img class="slide-image" src="imgs/pic23.png" style="top:62.44%; left:39%; width:28.21%; z-index:-1" />
<img class="slide-image" src="imgs/pic24.png" style="top:7.93%; left:47%; width:12.64%; z-index:-1" />




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# Sliders and Spinboxes
## Lets Make It Spin
<img class="slide-image" src="imgs/pic25.png" style="top:55%; left:22.46%; width:22.92%; z-index:-1" />
<img class="slide-image" src="imgs/pic26.png" style="top:55%; left:62.38%; width:22.92%; z-index:-1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 42px' } -->
# Range and Spinbox
- Restricts users to enter only numbers
  - Additional attributes **min**, **max** and **step** and **value**
  - Can become **Spinbox** or **Slider**, depending on the input type
```html
<input type="range" min="0" max="100" />
<input type="number" min="0" max="100" />
```
  - Have some **differences**on **different browsers**
  - Spinboxes do not work on **Firefox**
    - Shown as regular textboxes


<!-- attr: { id:'', class:'slide-section demo', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# Sliders and Spinboxes
## [Live Demo]()
<img class="slide-image" src="imgs/pic27.png" style="top:55%; left:5%; width:25%; z-index:-1" />
<img class="slide-image" src="imgs/pic28.png" style="top:55%; left:80%; width:25%; z-index:-1" />
<img class="slide-image" src="imgs/pic29.png" style="top:55%; left:35%; width:35%; z-index:-1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 42px' } -->
# Field Attributes from HTML 5
- **Autocomplete**
  - The browser stores the previously typed values
  - Brings them back on a later visit
- **Autofocus**
  - The field becomes on focus on page load
```html
<input type="text" name="firstName"
  autofocus="autofocus" />
```
- **Required**
  - The field is required to be filled/selected


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 40px' } -->
# Input Fields with Validation
- **Email** – provides a simple validation for email
  - Can be passed a pattern for validation
  - In a mobile device brings the email keyboard
  
```html
<input type="email" required="true" pattern="[^ @]*@[^ @].[^ @]"/>
```
- **URL** – has validation for url
  - In a mobile device brings the url keyboard
  
```html
<input type="url" required="true" />
```
- **Telephone**
  - Brings the numeric keyboard
  
```html
<input type="tel" required="true" />
```


<!-- attr: { id:'', class:'slide-section demo', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# HTML Forms Validation
## [Live Demo]()
<img class="slide-image" src="imgs/pic30.png" style="top:50%; left:14.03%; width:25%; z-index:-1" />
<img class="slide-image" src="imgs/pic31.png" style="top:50%; left:65.50%; width:25%; z-index:-1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 42px' } -->
# Tab Index
- The **tabindex** HTML attribute controls the order in which form fields and hyperlinks are focused when repeatedly pressing the **TAB** key
  - **tabindex="0"** (zero) – "natural" order
  - If **X < Y**, then elements with **tabindex="X"** are iterated before elements with **tabindex="Y"**
  - Elements with negative **tabindex** are skipped, however, this is not defined in the standard

```html
<input type="text" name="second" tabindex="10" />
<input type="text" name="first" tabindex="5" />
```



<!-- attr: { id:'', class:'slide-section demo', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# Tab Index
## [Live Demo]()
<img class="slide-image" src="imgs/pic32.png" style="top:50%; left:60%; width:29.97%; z-index:-1" />
<img class="slide-image" src="imgs/pic33.png" style="top:50%; left:13.10%; width:29.97%; z-index:-1" />




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# HTML Frames
## &#60;frameset>, &#60;frame> and &#60;iframe>
<img class="slide-image" src="imgs/pic34.png" style="top:55%; left:5%; width:42.31%; z-index:-1" />
<img class="slide-image" src="imgs/pic35.png" style="top:55%; left:59%; width:43.86%; z-index:-1" />


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 42px' } -->
# HTML Frames
- **Frames** provide a way to show multiple HTML documents in a single Web page
- The page can be split into separate views (frames) horizontally and vertically
- Frames were popular in the early ages of HTML development, but now their usage is rejected
- Frames are not supported by all user agents (browsers, search engines, etc.)
  - A **<noframes>**element is used to provide content for non-compatible agents.


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 42px' } -->
# HTML Frames – Demo

```html
<html>
  <head><title>Frames _Example_</title></head>
  <frameset cols="180px,*,150px">
    <frame src="left.html" />
    <frame src="middle.html" />
    <frame src="right.html" />
  </frameset>
</html>
```

<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'font-size: 42px' } -->
# Inline Frames: &#60;iframe>
- **Inline frames** provide a way to show one website inside another website:

```html
<iframe name="iframeYoutube"
        width="600" 
        height="400" 
        src="https://www.youtube.com/" 
        frameborder="yes" 
        scrolling="yes">
</iframe>
```


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'font-size: 42px' } -->
# HTML Forms and Frames

<img class="slide-image" src="https://raw.githubusercontent.com/TelerikAcademy/Common/master/revealjs-theme/css/imgs/questions-blue.png" style="width:80%; top:15%; left:10%" />
<div style="position: absolute; bottom: 1em; right: 0; font-size: 26px;">http://academy.telerik.com</div>