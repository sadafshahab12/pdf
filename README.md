# 📌 HTML Tags Cheat Sheet

A categorized list of HTML tags — including **standard, experimental, and deprecated** tags.  
This README is perfect as a quick reference while coding. 🚀

---

## ✅ Standard & Actively Used Tags (HTML5+)

### 1. Structure / Document Tags
```html
<html> <head> <body> <title> <base> <link> <meta> <style> <script> <noscript>

2. Sectioning / Semantic Tags
<header> <footer> <main> <nav> <section> <article> <aside> <h1> … <h6> <hgroup> <address> <search>

3. Text-Level Semantics
<p> <span> <strong> <em> <b> <i> <u> <mark> <small> <cite> <q> <blockquote> 
<abbr> <dfn> <time> <code> <kbd> <samp> <var> <sub> <sup> <del> <ins> <s> 
<br> <wbr> <bdi> <bdo>

4. Lists
<ul> <ol> <li> <dl> <dt> <dd>

5. Forms & Input
<form> <input> <label> <button> <textarea> <select> <option> <optgroup> 
<fieldset> <legend> <datalist> <output> <meter> <progress>

6. Tables
<table> <caption> <thead> <tbody> <tfoot> <tr> <td> <th> <col> <colgroup>

7. Media & Graphics
<img> <audio> <video> <source> <track> <picture> <canvas> <map> <area> 
<embed> <object> <param> <!-- ⚠️ Deprecated but still used in <object> -->

8. Interactive / Advanced
<details> <summary> <dialog> <template> <slot>

⚠️ Experimental (Not Widely Supported)
<fencedframe> <selectedcontent> <rtc>

❌ Deprecated / Obsolete Tags

These tags should not be used in modern HTML. Use CSS/JS alternatives instead.

<acronym>   → use <abbr>
<big>       → use CSS (font-size)
<center>    → use CSS (text-align: center)
<dir>       → use <ul>
<font>      → use CSS (font-*)
<frame>     → use <iframe>
<frameset>  → obsolete (use CSS Grid/Flexbox + <iframe>)
<marquee>   → use CSS animations
<nobr>      → use CSS (white-space: nowrap)
<noembed>   → no longer needed
<noframes>  → no longer needed
<param>     → replaced by <embed>
<plaintext> → use <pre>
<rb>        → replaced by <ruby> + <rt>
<rtc>       → experimental
<strike>    → use <s> or CSS (text-decoration)
<tt>        → use CSS (monospace font)
<xmp>       → use <pre>
