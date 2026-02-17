# ***WT Lecture***

<!--toc:start-->
- [***WT Lecture***](#wt-lecture)
  - [Different Server-side languages](#different-server-side-languages)
    - [Ruby](#ruby)
    - [Java](#java)
    - [Golang](#golang)
    - [C# (C Sharp)](#c-c-sharp)
  - [Client-side v/s Server-side](#client-side-vs-server-side)
    - [Client-side Scripting](#client-side-scripting)
    - [Server-side Scripting](#server-side-scripting)
  - [HTML](#html)
    - [Comments](#comments)
    - [Insert images](#)
<!--toc:end-->

## Different Server-side languages

### Ruby

- An **object oriented** *programming language* designed to be **simple to use**.
- It helps *developers* to write **clean and easily readable code**.

### Java

- Java is one of the **most used** programming languages and platforms.
- It is **highly scalable**
- Software- *Eclipse, Netbeans, VSCode*

### Golang

- It is a procedural and statically typed programming language having the syntax similar to C programming language.
- Sometimes it is termed as Go programming language.

### C# (C Sharp)

- A modern object-oriented language, often used to build web apps on Microsoft platforms.

## Client-side v/s Server-side

- When we need any kind of the information, most of the time, we get the help of the internet and we get the information. The internet provides us with the useful information easily.
- We use mobile phones, computers, tab, etc. We search for a lot of things in our daily life so we get information about all over the world. But we cannot get information by just only getting connected to the internet.
- We need a platform where we can search for our questions. The platform which provides such services is called a web browser. Without a web browser, internet will not be able to provide information.

**Web browser**:

- The web browser is an application software to explore 'www' (World Wide Web).
- It provides an interface between the server and the client and it requests to the server for web documents and services.
- It works as a compiler to render HTML.
- Ex:- Google Chrome, Microsoft Edge, etc

**Website Cookies:**

- the small files made by the browser to save information is called Cookies.
- They are designed to save the browser history.

### Client-side Scripting

- Web browser executes Client-side Scripting.
- Source code is used to transfer from web server to user over the internet.
- Used for validation and functionality.
- Allows for more interactivity.
- Cant be used to access the file-system or connect to the database on a web server.

### Server-side Scripting

- Web server are used to execute Server-side Scripting.
- it can access the file-system at the web-server.
- Can be written in any language.
- Used to retrieve and generate dynamic pages.
- Used to download plugins.

## HTML

### Some usable tags

- `<i>` tag- Italicizes text
- `<meta>` tag- provides additional information
  - name
  - description
  - date
  - refresh
  - redirect
  - cookies
  - author name
  - char set

### Comments

`<!-- Comment -->`

### Insert Images

you can insert images in html by using the `<img>` tag.
Eg:- `<img src="Image URL" ... attributes list>`.

### Tables

making a table requires `<table>` tag, as well as `<tr>` and `<td>` tags.
Eg:-

```html
<table border="1">
<tr>
<td>new</td>
<td>new</td>
<td>new</td>
</tr>
<tr>
<td>new</td>
<td>new</td>
<td>new</td>
</tr>
```

It shows up like this:

| new | new |
| --- | --- |
| new | new |
| new | new |
### Lists

collection of the data in ordered or unordered fashion.

types:
- `<ol>` or ordered list
- `<ul>` or unordered list
- `<dl>` or definition list

Eg:
```html
<ul>
<li>new1</li>
<li>new2</li>
<li>new3</li>
</ul>

<ol>
<li>mew1</li>
<li>mew2</li>
<li>mew3</li>
</ol>

<dl>
<dt>HTML</dt>
<dd>It stands for Hypertext Markup language</dd>
</dl>
```

### Linking documents

we use `<a href>` tag to link web-pages together.

## CSS

Cascading Style sheets, known as css, simplify the process of making website presentable. It changes the look and feel part of a webpage. Using CSS, you can control the color of the text, the style of the fonts, and the spacing between the paragraphs, how columns are sized and made out, what background images or colors are used, etc.

### CSS

CSS deals with different style rules that are interpreted by the browser and then are applied to the corresponding elements in your document.

A style group is made of 3 parts:
- selector:- is an HTML tag in which the style will be applied. This could be any tag, like body tag or head tag.
- property:- It is a type of attribute of the HTML tag. Put simply, all the HTML attributes are converted into CSS properties. They could be colour, properties, etc.
- value:- These are assigned to the properties, for eg: colour property can have either "#red" or "#f1f1f1".

You can define the selectors in different ways:
- type selector: this is 
- Universal selector.
- Descendant selector: suppose you want to apply a style rule to an element only when it is inside a particular element.
- class selectors: all the elements having that class.

### types of CSS

U can use style attributes in line the HTML.
This will apply to that element only.