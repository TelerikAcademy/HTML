<!-- section start -->
<!-- attr: { class:'slide-title', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# HTML Forms and Frames

<div class="signature">
    <p class="signature-course">HTML Basics</p>
    <p class="signature-initiative">Telerik Software Academy</p>
    <a href="http://academy.telerik.com" class="signature-link">http://academy.telerik.com</a>
</div>

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic00.png" style="top:35%; left:60%; width:40%; z-index:-1; border-radius:15px;" /> -->

<!-- section start -->
<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Table of Contents
- [HTML Forms](#/form)
  - [Form Fields and Fieldsets](#/field)
  - [Buttons](#/button)
  - [Checkboxes and Radio Buttons](#/checkbox)
  - [Select Fields](#/select)
  - [Hidden Fields](#/hidden)
  - [Sliders and Spinboxes](#/slider)
  - [Validation Fields](#/validation)
- HTML Frames
  - [Frame and **noframe** tags](#/noframe)
  - [**iframe** tag](#/iframe)
  <!-- <img class="slide-image" showInPresentation="true" src="imgs/pic03.png" style="top:20%; left:76.72%; width:24.24%; z-index:-1; border-radius:15px;" /> -->

// 
<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # HTML Forms
## Entering User Data from a Web Page -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic07.png" style="top:55%; left:25%; width:20%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic08.png" style="top:55%; left:55%; width:25%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'form', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="form"></a>What are HTML Forms?
- The **primary** method for gathering data from site visitors
- HTML Forms can contain
  - **Text** fields for the user to type
  - **Buttons** for interactions like<br /> "**Register**", "**Login**", "**Search**"
  - **Menus**, **Sliders**, etc…
- Check Google, Yahoo, Facebook
  - Google search field is a simple **Text field**
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic11.png" style="top:32.62%; left:80.00%; width:20.28%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
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

<div class="fragment balloon" style="top:50%; left:41%;">The "action" attribute tells where the form data should be sent</div>
<div class="fragment balloon" style="top:30%; left:41.43%;">The "method" attribute tells how the form data should be sent – via GET or POST request</div>


<!-- attr: { id:'field', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 0.8em' } -->
# <a id="field"></a>Text Fields
- **Single-line** text input fields:

```html
<input type="text" name="FirstName" value="This is a text field" />
```
- **Multi-line** text input fields (`textarea`):

```html
<textarea name="Comments">
    This is a multi-line text field
</textarea>
```
- **Password** input – a text field which masks the entered text with `*` signs

```html
<input type="password" name="pass" />
```

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic12.png" style="top:13%; left:70%; width:25%; z-index:1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic13.png" style="top:30.63%; left:76%; width:20%; z-index:1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic14.png" style="top:68%; left:70%; width:25%; z-index:1; border-radius:15px;" /> -->


<!-- attr: { id:'button', showInPresentation:true, hasScriptWrapper:true } -->
# <a id="button"></a>Buttons
- **Reset** button – brings the form to its initial state

```html
<input type="reset" name="resetBtn"
  value="Reset the form" />
```
- **Submit** button:

```html
<input type="submit" name="submitBtn" value="Submit" />
```

<!-- attr: { id:'button', showInPresentation:true, hasScriptWrapper:true } -->
# <a id="button"></a>Buttons
- **Image** button – acts like submit but image is displayed and click coordinates are sent

```html
<input type="image" src="submit.gif"
  value="click me" alt="Submit" />
```
- **Ordinary** button – no default action, used with JS

```html
<input type="button" value="Apply Now" />
```


<!-- attr: { id:'checkbox', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="checkbox"></a>Checkboxes and Radio Buttons
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

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic15.png" style="top:14%; left:50%; width:15%; z-index:-1; border-radius:15px;; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic16.png" style="top:35%; left:50%; width:25%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'select', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="select"></a>Select Fields
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

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic17.png" style="top:50%; left:75%; width:10.80%; z-index:1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic18.png" style="top:11.46%; left:75%; width:24.35%; z-index:1; border-radius:15px;" /> -->


<!-- attr: { id:'hidden', class:'slide', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="hidden"></a>Hidden Fields
- **Hidden** fields contain invisible data

```html
<input type="hidden" name="Account"
  value="This is a hidden text field" />
```
  - Not shown to the user
  - Used by **JavaScript** and **server-side** code
    - **ViewState**, **SessionState** in ASP.NET


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
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
  - Required to pass accessibility validation


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Fieldsets
- **Fieldsets** are used to enclose a group of related form fields:

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
- The <code>&lt;legend&gt;</code> is the fieldset's title


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # HTML Forms <br /> Inputs Fields -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/04.%20HTML-Forms-and-Frames/demos/1.%20Form-input-fields.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic19.png" style="top:11.46%; left:7%; width:21.16%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic20.png" style="top:50.25%; left:8%; width:21.16%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic21.png" style="top:9.99%; left:78%; width:21.16%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic22.png" style="top:52.75%; left:80%; width:21.16%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic23.png" style="top:62.44%; left:39%; width:28.21%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic24.png" style="top:7.93%; left:47%; width:12.64%; z-index:-1; border-radius:15px;" /> -->




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Sliders and Spinboxes
## Lets Make It Spin -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic25.png" style="top:55%; left:22.46%; width:22.92%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic26.png" style="top:55%; left:62.38%; width:22.92%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'slider', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="slider"></a>Range and Spinbox
- Restricts users to enter only numbers
  - Additional attributes **min**, **max** and **step** and **value**
  - Can become **Spinbox** or **Slider**, depending on the input type

```html
<input type="range" min="0" max="100" />
<input type="number" min="0" max="100" />
```
  - Have some **differences** on **different browsers**
  - Spinboxes **do not work** on all the browsers
    - Shown as regular textboxes


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Sliders and Spinboxes -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/04.%20HTML-Forms-and-Frames/demos/2.%20Sliders-spinboxes.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic27.png" style="top:55%; left:5%; width:25%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic28.png" style="top:55%; left:75%; width:20%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic29.png" style="top:55%; left:35%; width:35%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
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


<!-- attr: { id:'validation', showInPresentation:true, hasScriptWrapper:true, style:'font-size:0.75em' } -->
# <a id="validation"></a>Input Fields with Validation
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
  - Brings the numeric keyboard (currently supported only in Safari 8)

```html
<input type="tel" required="true" />
```


<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # HTML Forms Validation -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/04.%20HTML-Forms-and-Frames/demos/3.%20Forms-validation.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic30.png" style="top:50%; left:14.03%; width:20%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic31.png" style="top:50%; left:65.50%; width:20%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Tab Index
- The `tabindex` HTML attribute controls the order in which form fields and hyperlinks are focused when repeatedly pressing the **TAB** key
  - `tabindex=0` (zero) – "natural" order
  - If `X < Y`, then elements with `tabindex="X"` are iterated before elements with `tabindex="Y"`
  - Elements with negative `tabindex` are skipped, however, this is not defined in the standard

```html
<input type="text" name="second" tabindex="10" />
<input type="text" name="first" tabindex="5" />
```



<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Tab Index -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/04.%20HTML-Forms-and-Frames/demos/4.%20Tab-index.html)
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic32.png" style="top:50%; left:63%; width:20%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic33.png" style="top:50%; left:16%; width:20%; z-index:-1; border-radius:15px;" /> -->




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # HTML Frames
## `<frameset>`, `<frame>` and `<iframe>` -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic34.png" style="top:55%; left:14%; width:30%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic35.png" style="top:55%; left:54%; width:31%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'noframe', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="noframe"></a>HTML Frames
- **Frames** provide a way to show multiple HTML documents in a single Web page
- The page can be split into separate views (frames) horizontally and vertically
- Frames were popular in the early ages of HTML development, but now their usage is rejected
- Frames are not supported by all user agents (browsers, search engines, etc.)
  - A <code>&lt;noframes&gt;</code> element is used to provide content for non-compatible agents.


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
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

_Note_: the target attribute applied to the <code>&lt;a&gt;</code> elements in the left frame.

<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # HTML Frames -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/04.%20HTML-Forms-and-Frames/demos/5.%20Frames.html)

<!-- attr: { id:'iframe', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="iframe"></a>Inline Frames: `<iframe>`
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
<!-- attr: { class:'slide-section demo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # iframes -->
## [Demo](https://github.com/TelerikAcademy/HTML/tree/master/Topics/04.%20HTML-Forms-and-Frames/demos/6.%20IFrame.html)

<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:false, style:'font-size: 42px' } -->
<!-- # HTML Forms and Frames
## Questions? -->

<!-- <img class="slide-image" showInPresentation="true" src="https://raw.githubusercontent.com/TelerikAcademy/Common/master/revealjs-theme/css/imgs/questions-blue.png" style="width:60%; top:15%; left:10%" /> -->

<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Free Trainings @ Telerik Academy
- Web front-end track
    - [html.telerik.com](http://academy.telerik.com/student-courses/web-design-and-ui/about)
  - Telerik Software Academy
    - [academy.telerik.com](academy.telerik.com)
  - Telerik Academy @ Facebook
    - [facebook.com/TelerikAcademy](facebook.com/TelerikAcademy)
  - Telerik Academy Learning System
    - [telerikacademy.com](telerikacademy.com)
