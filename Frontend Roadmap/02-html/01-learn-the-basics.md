# Learn the Basics

## What is HTML?


- HTML stands for `Hyper Text Markup Language`
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

## A Simple HTML Document / Basit bir HTML Dökümanı

    <!DOCTYPE html>
    <html>
    <head>
    <title>Page Title</title>
    </head>
    <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

    </body>
    </html>

### Example Explained

- The <!DOCTYPE html> declaration defines that this document is an HTML5 document. *Döküman HTML5 dökümanıdır diye tanımlar*
- The `<html>` element is the root element of an HTML page *HTML sayfasının kökü*
- The `<head>` element contains meta information about the HTML page. *Meta bilgileri bu tag ile, sayfada gözükmez*
- Thes `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab) *HTML sayfasının başlığı bu tag ile*
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc. *Sayfanın içeriklerinin hepsi bu body tagının içinde olacak*


- The `<h1>` element defines a large heading *Başlık tagı*
- The `<p>` element defines a paragraph *Paragraf tagı, doğal olarak yeni bir paragrafa, alt satıra geçer.*

### HTML Headings / HTML Başlıklar

HTML headings are defined with the `<h1>` to `<h6>` tags. *Başlıklar h1 den h6 ya kadar, h1 en önemlisi h6 en az önemli*

    <h1>This is heading 1</h1>
    <h2>This is heading 2</h2>
    <h3>This is heading 3</h3>

### HTML Paragraphs / Paragraflar

HTML paragraphs are defined with the `<p>` tag *Paragraflar `<p>` tagıyla. Doğal olarak alt satıra geçilir/paragraf alınır.*

    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>

### HTML Links / Linkler

HTML links are defined with the `<a>` tag *HTML linkleri `<a>` tagıyla*

    <a href="https://www.duckduckgo.com">This is a link</a>   

### HTML Images / Resimler

HTML images are defined with the `<img>` tag.

     <img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">

### HTML Styles / Stiller

The HTML style attribute is used to add styles to an element, such as color, font, size, and more. *renk, yazı tipi, boyut gibi stil verebiliriz.*

    <p style="color: red;">I am Red</p>
    <p style="color: blue;">I am Blue</p>
    <p style="font-size: 30px;">I am Big</p>

<p style="color: red;">I am Red</p>
<p style="color: blue;">I am Blue</p>
<p style="font-size: 30px;">I am Big</p>

### HTML Text Formatting / Format

    <p><b>This text is bold</b></p>
    <p><i>This text is italic</i></p>
    <p>This is<sub> subscript</sub> and <sup>superscript</sup></p>


<p><b>This text is bold</b></p>
<p><i>This text is italic</i></p>
<p>This is<sub> subscript</sub> and <sup>superscript</sup></p>

### HTML Tables / Tablo

    <table style="width:100%">
      <tr>
        <th>Firstname</th>
        <th>Lastname</th>
        <th>Age</th>
      </tr>
      <tr>
        <td>Jill</td>
        <td>Smith</td>
        <td>50</td>
      </tr>
      <tr>
        <td>Eve</td>
        <td>Jackson</td>
        <td>94</td>
      </tr>
      <tr>
        <td>John</td>
        <td>Doe</td>
        <td>80</td>
      </tr>
    </table>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

### HTML Lists / Listeler

##### Unordered List / Düzensiz Liste

    <ul>
      <li>Coffee</li>
      <li>Tea</li>
      <li>Milk</li>
    </ul>  

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>  

##### Ordered List / Düzenli Liste

    <ol>
      <li>Coffee</li>
      <li>Tea</li>
      <li>Milk</li>
    </ol>  

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>  

---

This is enough for now.


---

# Useful Links

[HTML Tutorial - W3Schools](https://www.w3schools.com/html/default.asp)
