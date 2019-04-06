# Welcome to HTML5 hello-world.  :computer:

In this section we will learn about the different types of HTML tags/elements, why we would use them and when?

There are many different types of tags/elements in HTML5 and they are one and the same.

Tags/elements in HTML are the building blocks of any website or application.

___

### HTML stands for   :arrow_down:
```
Hyper Text Mark-Up Language
```

If we think of HTML5 being the skeleton of our website then we would not be far away with our presumption.
All HTML5 pages are called <b>"Documents"</b> and are the building blocks for any website or application. HTML <b>"Documents"</b> are usually written <b>"Semantically"</b> which means each element has a specific use case for its purpose. For example, If we want a main <b>Heading</b> for our website, we would use a &#60;h1&#62; element. As <b>semantically</b> this makes sense as a &#60;h1&#62; element is the largest header tag we can use. Semantically, you would only ever use <b>one</b> &#60;h1&#62; element per document. 

* You can read and research the history of HTML and it's previous versions here:

:x: [A breif history of html](https://www.wired.com/1997/04/a-brief-history-of-html/)

* Read more about Semantic HTML here:

:x: [Semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)

___

## Typical HTML5 Element structure

Simple element structure...
```
<elementName> </elementName>
```
Lets try using the &#60;html&#62; element.

```
<html> __content goes in here__  </html>
```

### Here are some more commonly used HTML5 Elements.   :heavy_exclamation_mark:

#### Remember!
Some elements in HTML are styled differently. This means some of them display "In-Line" and some of them display as "Block". We will get to what both these display styles mean when we start <b>CSS3</b>.

___

## The &#60;head&#62; element   :arrow_down:
The &#60;head&#62; element is used to define the <b>meta data</b> in our HTML document. It looks like this:

&#60;head&#62; &#60;/head&#62;

This element goes above the &#60;body&#62; element and contains language information and font type information. This allows our browser to read and display content accordingly.

### Typical use case

```
<head>

<title>Hello World</title>

 </head>
 
 ```

* More information on <b>meta data</b> can be found here:


:x: [HTML Meta Data](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)


* Read more about the &#60;head&#62; &#60;/head&#62; element here:

:x: [HTML Head Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head)

___

## The &#60;title&#62; element   :arrow_down:
The &#60;title&#62; element is used to define the <b>Title</b> in our HTML document. It looks like this:

&#60;title&#62; &#60;/title&#62;

This element goes inside the &#60;head&#62; element and contains the title of our webpage/website. This allows our browser to read and display content accordingly.

### Typical use case

```
<head>

<title>Hello World</title>

 </head>
 
 ```

 This will display the title of the Website in the browsers tab! 

 ### Check here for screenshots and help

 ![](Images/title.png)


* More information on <b>meta data</b> can be found here:


:x: [HTML Meta Data](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)


* Read more about the &#60;head&#62; &#60;/head&#62; element here:

:x: [HTML Head Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head)

___

## The &#60;body&#62; element   :arrow_down:
The &#60;body&#62; element is used to define the <b>main</b> content in HTML document. It looks like this:

&#60;body&#62; &#60;/body&#62;

In most cases, all other elements will go inside the body tags.
This element contains the main content of our website. Semantically this is the <b>Body</b> of the website. The &#60;head&#62; and &#60;html&#62; elements do not go in the &#60;body&#62; element. We will look into this in more detail further on.

### Typical use case

```
<body>

<h1>Hello World</h1>

 </body>
 
 ```

* Read more about the &#60;body&#62; &#60;/body&#62; element here:

:x: [HTML Body Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body)


___

## The &#60;h&#62; element   :arrow_down:
The &#60;h&#62; element is used to define a <b>Header</b> in HTML. It looks like this:

&#60;h1&#62;&#60;/h1&#62;

The <b>Header</b> element is a very descriptive tag. There are 6 header tags in total. They range from &#60;h1&#62; to a &#60;h6&#62;. The size of the text get's smaller the higher the h number goes. So a &#60;h1&#62; tag is the largest font-size and the &#60;h6&#62; tag has the smallest font-size.

### Typical use case

```
<h1>Hello Wigan Coding Meet-Up!</h1> 
<h2>Hello Wigan Coding Meet-Up!</h2> 
<h3>Hello Wigan Coding Meet-Up!</h3> 
<h4>Hello Wigan Coding Meet-Up!</h4> 
<h5>Hello Wigan Coding Meet-Up!</h5> 
<h6>Hello Wigan Coding Meet-Up!</h6> 

 ```

* Read more about the H elements here:

:x: [HTML H Elements (Header)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)

___

## The &#60;p&#62; element   :arrow_down:
The &#60;p&#62; element is used to define a <b>Paragraph</b> in HTML. It looks like this:

&#60;p&#62;&#60;/p&#62;

Notice how we have an opening &#60;p&#62; and a closing &#60;/p&#62; tags. Most elements in HTML require opening and closing tags. The difference if you look closely, is a /.
There are elements that don't require a closing tag, we will get to those later!

### Typical use case

```
<body>

<p>
Hello World! Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
</p>

 </body>
 
 ```

* Read more about the p element here:

:x: [HTML p Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)

___

## A HTML5 Boilerplate

In HTML5 there is a certain structure we <b>MUST</b> adhered to when writting our code. This structure is commonly used in most web browsers. 

### Check here for a default hello-world HTML5 Boilerplate.

```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="main.css">
  <title>Hello Wigan Coding Meet Up!</title>
</head>




<body>
  <h1 class="header">Hello World!</h1>
  <br>
  <h1>Hello. I am a H1</h1>
  <h2> I am a H2</h2>


  <hr>
  <br><br>


</body>

</html>
```

What's that I can see? A &#60;!DOCTYPE html&#62; element? Other elements we havn't talked about yet? Time for some more reading!

* Learn more about HTML DOCTYPE here:
[HTML5 DOCTYPE](https://developer.mozilla.org/en-US/docs/Glossary/Doctype)

* Learn more about HTML5 &#60;meta&#62; element here:
[HTML5 meta element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta)

* Learn more about HTML5 &#60;link&#62; element here:
[HTML5 link element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link)

* Learn more about HTML5 &#60;html&#62; element here:
[HTML5 html element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html)
