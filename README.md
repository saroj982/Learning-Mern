# Learning-Mern

## HTML/CSS/JS

## Web

- www: World wide web
- system of interlinked docs accessed through the internet using browser.
- Websites are made of HTML (structure), css(styling), and javascript(Behavior).

## Client-Server Model

- Client: The browser or app that sends requests to server.
- Server: The machine thats process the requests and send response (html, css ,data).

### HTML

- Hypertext Markup language

1. Text Elements

- Headings -> <h1> - <h6>
- paragraph -> <p>
- Bold -> <strong>
- Emphasize -> <em>
- subscript -> <sub>
- superscript -> <sup>
- preformatted text -> <pre>

2. Link and Media

- Anchor -> <a>
- Images -> <img>
- Videos -> <video>

3. Lists

- Ordered list -> <ol>
- Unordered list -> <ul>
- list items -> <li>

4. Misc

- line break -> <br>
- Divider -> <hr>
- Iframe -> <iframe> ->youtube video.

5. Table

- Table -> <table>
- Table row -> <tr>
- Table data -> <td>
- Table heading -> <th>
- Table head -> <thead>
- Table body -> <tbody>
- Table footer -> <tfoot>
- Rowspan -> <rowspan="2">
- Colspan -> <colspan="2">

6. Form

- Form -> <form action="">
- input -> <input type=""> -> text,number,email, tel, checkbox, radio, file, date, time, range, color, password, submit, search etc.
- Properties -> placeholder, min, max, placeholder, value, checked accept( for image:.jpeg,.png), multiple for multiple file select, required, disabled, selected etc.
- for and id should be same.
- label -> <label for=""></label>
- Text Area -> <textarea>
- Select and Option for dropdown-> <select> <option></option> </select>
- search -> input type search then list="animals" then datalist id same as list name. then inside options.

7. Inline & Block elements

- Inline elements occupies only the required space. for eg -> <a>, <img>, <video>, <span> etc.
- Block elements occupy full width of the screen like <h1>-<h6>, <p>, <div>, <li>

8. Semantics

- All html elements must be in lowercase.
- Use proper elements as per their position and usage.
- Always add 'alt' property in the image tag
- Always add 'title' property in the button tag especially icon only button.
- HTML file name must be in kebab case. for e.g in small letter if two words then 'hello-world.html'.
- Always format your code using shortcut key alt+shift+f.
- In each html file/page. there must be at least one <h1></h1> tag.

9.  HTML Page
      <body>
        <header>
            <nav></nav>
        </header>
        <main>
            <aside>
                <div></div>
                <div></div>
                <div></div>
            </aside>

            <section></section>
            <section></section>
            <section></section>
            <section></section>
        </main>
        <footer></footer>

    </body>

### CSS: Cascading Style Sheet

- Website styling like color, font-size, aligmnent, spacing etc.

**_Syntax_**
<selector>{
property:value;
property:value;
...
}
For example:
h1{
color:red;
Font-Family:San-serrif
}

## Selectors

1.  Element -> h1, img, p, span etc. (lowest priority)
2.  Class -> (priority id > class > element){
    .classname{
    property:value;
    }
    }
3.  id ->(Highest priority) {
    #idname{
    property:value;
    }
    }

## Class vs id## (Semantics)

- For css, always uses class
- for js, use id

## css Usage

1. Inline
2. Internal (not used often)
3. External

### CSS Properties###

1. color, Background color

- rgb(red, green, blue)-> rgb range(0-255,0-255,0-255).(0,0,0)->black, (255,255,255)->white etc.
- hexadecimal (0-F) eg:6digits->FF0000 =red color.
- rgba(255,255,0,0.5)

2. Text -> align, decoration, transform, word-spacing, lettor-spacing, text-shadow , line-height etc.
3. Font -> size, weight, style, family
4. Box model:
<!-- margin->border->padding->content -->

- margin-> inline , block, right, left, top, bottom etc.
- padding -> inline , block, right, left, top, bottom etc.
- border -> size,type,color -> dotted, solid, dashed etc. border-radius etc.

5. Display -> block inline inline-block none
6. Flex->display flex, display-direction->row,column,reverse, justify-content->space between,evenly, around, align items->start,end,center,flex-wrap->nowrap,wrap,Gap->10px.
7. List -> list style-> circle, square, none, disc etc.
8. Units-> rem,px,%,vh etc
   rem-> font-size, margin, padding, gap
   px-> border, border-radius, shadow
   %->width
   vh-> height for herosection
9. Pseudeo-class ->hover, active, focus, checked, disabled, required etc.
10. Overflow -> auto, hidden, scroll, visible.
11. Position -> position: relative,
    absolute(tricky-> if p->relative tesko class ma hunxa natra body ko relative ma hanxa), fixed,
    sticky(header).
12. Table -> border-collapse:seperate, collapse nthchild->bgc
13. Form
14. Icon
15. Background image
16. Transform
17. Animation
18. Responsive design
19. Grid
20. Variables
21. Misc
