<!-- section start -->
<!-- attr: { class:'slide-title', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Semantic Web
## How to Use HTML Elements Properly?
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic00.png" style="top:-5%; left:20%; width:25%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic01.png" style="top:51.94%; left:60%; width:40%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic02.png" style="top:63%; left:5%; width:35%; z-index:-1; border-radius:15px;" /> -->




<!-- section start -->
<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Table of Contents
- [Web Page](#/webpage)
  - [HTML, CSS and JavaScript](#/html)
- [The Semantic HTML](#/semantic)
- [HTML5 Semantic Tags](#/html5)
- [Other Semantics](#/other)
- [Accessibility](#/access)
- [Search Engine Optimization](#/seo)
- [Structured Data Markup](#/datamarkup)

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic03.png" style="top:28.21%; left:66.06%; width:36.93%; z-index:-1; border-radius:15px;" /> -->




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Web Page -->

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic04.png" style="top:50%; left:30%; width:40%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'webpage', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="webpage"></a>The Elements of a Web Page
- A Web page consists of:
  - HTML markup
  - CSS rules
  - JavaScript code
    - JS libraries
  - Images
  - Other resources
    - Fonts, audio, video, Flash, Silverlight, etc…

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic05.png" style="top:15%; left:57.19%; width:38.68%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'html', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="html"></a>The Elements of a Web Page: HTML Markup
- The HTML is used to define<br />the **content** of a Web page
  - Not the layout
  - Not the decorations
- HTML's role is to present the information in a **meaningful** manner
  - Like a paper document
  - Define headers, paragraphs, text boxes, etc…
  - Not define size, color and/or positioning

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic06.png" style="top:13%; left:60%; width:20%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# The Elements of a Web Page: CSS Rules
- Cascading Style Sheets (**CSS**) is the way to make a Web page look pretty
  - Define **styling rules**
    - Fonts, colors, positioning, etc.
  - Define the layout of the elements
  - Define the presentation
- The CSS files are attached to a web page and the browser applies these styles to elements

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic07.png" style="top:27.33%; left:79.53%; width:24%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# The Elements of a Web Page: JavaScript Code
- **JavaScript** is the programming language for the Web
  - Makes the Web pages dynamic
  - Dynamically adding / removing HTML elements, applying styles, etc.
  - Modern JavaScript UI libraries provide UI components like dialog boxes, grids, tabs, etc.
- Like CSS the JavaScript files are attached to a web page

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic08.png" style="top:70%; left:80%; width:20%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# The Elements of a Web Page: Other Resources
- Other resources are needed for a Web page to run properly
  - Images, fonts (glyph icons), audio, video files
  - Flash / Silverlight / ActiveX objects

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic09.png" style="top:52.58%; left:42.41%; width:20.69%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic10.png" style="top:67.12%; left:72.79%; width:10.66%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic11.png" style="top:51.52%; left:88.60%; width:10.66%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic12.png" style="top:66.76%; left:7.20%; width:10.66%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic13.png" style="top:51.60%; left:21.24%; width:10.66%; z-index:-1; border-radius:15px;" /> -->




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # The Semantic HTML -->

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic14.png" style="top:45%; left:12%; width:39.05%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic15.png" style="top:45%; left:60%; width:31%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'semantic', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="semantic"></a>Semantic HTML
- **Semantic** HTML is:
  - The use of HTML markup to reinforce the semantics of the information in Web pages
    - Make the content understandable for computers
  - Rather than merely to define its presentation
  - A kind of **metadata** about the HTML content
- Semantic HTML is processed by regular Web browsers and other user agents
  - CSS is used to suggest its presentation to human users

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic16.png" style="top:29%; left:83.27%; width:19.47%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Why Use Semantic HTML?
- Semantic HTML is:
  - Easier to read by developers, parsers, bots, machines, AIs
  - A way to show the search engines the correct content

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic17.png" style="top:45%; left:0%; width:25%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic18.png" style="top:45%; left:40%; width:20%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic19.png" style="top:45%; left:75%; width:25.72%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# How To Write Semantic HTML?
- Just follow some guidelines when creating a Web site
  - Use HTML5 semantic tags
    - `<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`
  - Use Headings when you need to structure the content into sub-headings
    - In increasing order, staring with `<h1>`
  - Do not use empty tags
    - Like a clearing `<div>`

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic20.png" style="top:55%; left:75%; width:22.52%; z-index:-1; border-radius:15px;" /> -->


<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # HTML5 Semantic Tags -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic21.png" style="top:50%; left:27.5%; width:45%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'html5', showInPresentation:true, hasScriptWrapper:true, style:'font-size:42px' } -->
# <a id="html5"></a>HTML5 Semantic Tags
- HTML5 introduces **semantic structure tags**
  - Imagine the following site:
  - This is a common Web page structure
    - Used in 90% of the web sites

<img class="slide-image" showInPresentation="true" src="imgs/pic22.png" style="top:38%; left:25%; width:50%; z-index:-1; border-radius:15px;" />


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # HTML5 Semantic Tags -->
- This can be created using all kind of HTML elements
  - `<div>`, `<span>`, even `<p>`
  - Browsers will render invalid / wrong / pseudo valid HTML
- The correct way: use the HTML 5 semantic tags:

```html
<header> … </header>
<nav> … </nav>
<main> … </main>
<article> … </article>
<section> … </section>
<aside> … </aside>
<footer> … </footer>
```


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# HTML5 Structure Tags
- `<main>`
  - Specifies the main content of a document ([info](http://html5doctor.com/the-main-element/))
  - There must not be more than one `<main>` element in a document
- `<header>`
  - Site header or section header or article header
  - Could include navigation (`<nav>`)
- `<footer>`
  - Site footer (sometime can be a section footer)
  - Providing author, copyright data, etc.


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# HTML5 Structure Tags
- `<nav>`
  - Defines a set of navigation links.
  - E.g. site navigation (usually in the header)
- `<aside>`
  - Content slightly related to primary content
  - E.g. sidebar (usually on the left or on the right)
- `<section>`
  - Grouping of content usually with a heading, similar to chapters
  - Site section (e.g. news, comments, links, …)


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# HTML5 Content Tags
- `<article>`
  - Independent content such as blog post or an article (e.g. news item)
- `<details>` + `<summary>`
  - Specifies additional details that the user can view or hide on demand (accordion-like widget)
- `<time>`
  - Specifies date / time (for a post / article / news)
- `<mark>`
  - Defines marked/highlighted text


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# HTML5 Content Tags
- `<figure>`
  - Grouping stand-alone content (video or image)
  - Figure (a figure, e.g. inside an article)
- `<figcaption>`
  - A caption of a figure (inside the `<figure>` tag)
- `<video>` ([info](http://www.w3schools.com/html/html5_video.asp))
  - Video element (uses the built-in player)
- `<audio>` ([info](http://www.w3schools.com/html/html5_audio.asp))
  - A standard for playing audio files (built-in player)


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# HTML5 Content Tags
- `<dialog>`
  - Defines a dialog box or window
- `<meter>` / `<progress>`
  - Defines a scalar measurement within a<br />known range (a gauge) or task progress
- `<output>`
  - Defines the result of a calculation
- `<wbr>`
  - Defines a possible line-break
- [More info](http://www.w3schools.com/html/html5_new_elements.asp)  

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic24.png" style="top:39.91%; left:85.14%; width:17.96%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic25.png" style="top:19.39%; left:85.14%; width:17.96%; z-index:-1; border-radius:15px;" /> -->




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Other Semantics
## Headings, ems, strongs -->

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic26.png" style="top:55%; left:35%; width:30%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'other', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="other"></a>Other Semantics
- Headings
  - Always use headings (`<h1>` – `<h6>`) when you need a heading or title
    - Like in a MS Word document
    - Google uses it to mark important content
- Strong `<strong>` vs. Bold `<b>`
  - `<b>` does not mean anything
    - It just makes the text bolder
  - `<strong>` marks the text is "stronger" than the other, surrounding text


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Other Semantics
- Emphasis `<em>` vs. Italic `<i>`
  - Emphasis does not always mean, that the code should be italic
    - It could be bolder, italic and underlined
  - The styles for the emphasis text should be set with CSS
    - Not by HTML
- Old browsers (like IE6)?
  - Use [Modernizr](http://modernizr.com/) or [HTML5shiv](http://code.google.com/p/html5shiv/)




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Accessibility
## “A person’s a person,no matter how small” -->

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic27.png" style="top:55%; left:20%; width:60%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'access', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="access"></a>Accessibility
- Craft content minding disabled users
  - **Blind** - include text equivalents of images, use labels in forms
  - **Colorblind** - do not convey information using color only
  - **Visually impaired** - avoid small font sizes
  - **Epileptic** - avoid flashing content (3Hz or more)
  - **Physical disabilities** - avoid functionality that relies only on the mouse or keyboard


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Accessibility
- Why implement accessibility?
  - Some accessibility features are mandatory for government sites in some countries (US, NL, SW)
  - “Everyone gets visited by a very important blind user, named Google”
  - Some SEO and accessibility considerations overlap


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Accessibility
- Standards
  - Web Content Accessibility Guidelines (WCAG) - http://www.w3.org/WAI/intro/wcag
  - Section 508 - http://www.section508.gov
- Tools
  - Will never replace manual testing, but may help
  - WAVE - http://wave.webaim.org/




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Search Engine Optimization
## Getting ahead in search engines -->

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic28.png" style="top:55%; left:15%; width:25%; z-index:-1; border-radius:15px;" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic29.png" style="top:55%; left:50%; width:40%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'seo', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# <a id="seo"></a>Search Engine Optimization
- Search engines use so-called “**crawlers**” to get the content of the page and index it
- The crawlers weigh the data on the page
  - `<title>`, **page URL** and **headings** have great weight
  - Links from highly valued pages to your page increase its value (Google **Page Rank**)
  - Add alt text to images
  - Use relevant keywords in the content and `<meta>` tags
- No SEO technique will replace good content




<!-- section start -->
<!-- attr: { class:'slide-section', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Structured Data Markup
## Annotate your content so machines can understand it -->

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic30.png" style="top:60%; left:20%; width:60%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { id:'datamarkup', showInPresentation:true, hasScriptWrapper:true, style:'font-size: 40px' } -->
# <a id="datamarkup"></a>Structured Data Markup
- A standard way to annotate your content so machines can understand it
- Google (and other search engines) can
  - use that data to index your content better
  - present it more prominently in search results
    ![google search link](imgs/pic31.png)
  - Provide answers from the Knowledge Graph

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic32.png" style="top:76%; left:15%; width:45%; z-index:-1; border-radius:15px;" /> -->


<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
# Structured Data Markup
- Three alternative formats:
  - Microdata and RDFa
    - Define new HTML attributes
      - [More info](http://schema.org/docs/gs.html#microdata_how)
  - JSON-LD
    - Newest and simplest markup format
    - Embed a block of JSON data inside a script tag
      - [Specification](http://www.w3.org/TR/json-ld/)
      - [_Examples_](http://json-ld.org/playground/)

<!-- section start -->
<!-- attr: { showInPresentation:true, hasScriptWrapper:true, style:'font-size: 42px' } -->
<!-- # Semantic Web -->

<!-- <img class="slide-image" showInPresentation="true" src="https://raw.githubusercontent.com/TelerikAcademy/Common/master/revealjs-theme/css/imgs/cat-questions.png" style="width:80%; top:15%; left:10%" /> -->

<!-- attr: { showInPresentation:true, hasScriptWrapper:true } -->
# Free Trainings @ Telerik Academy
- Web front-end track
    - [html.telerik.com](http://academy.telerik.com/student-courses/web-design-and-ui/about)
  - Telerik Software Academy
    - [telerikacademy.com](https://telerikacademy.com)
  - Telerik Academy @ Facebook
    - [facebook.com/TelerikAcademy](facebook.com/TelerikAcademy)
  - Telerik Academy Learning System
    - [telerikacademy.com](https://telerikacademy.com)
